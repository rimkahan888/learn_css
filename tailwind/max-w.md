Here’s a **TL;DR list of `max-w-*` (max-width) options in Tailwind CSS** for controlling element width limits:

---

### **Fixed Widths**  
- `max-w-0` → `0px`  
- `max-w-xs` → `20rem` (320px)  
- `max-w-sm` → `24rem` (384px)  
- `max-w-md` → `28rem` (448px)  
- `max-w-lg` → `32rem` (512px)  
- `max-w-xl` → `36rem` (576px)  
- `max-w-2xl` → `42rem` (672px)  
- `max-w-3xl` → `48rem` (768px)  
- `max-w-4xl` → `56rem` (896px)  
- `max-w-5xl` → `64rem` (1024px)  
- `max-w-6xl` → `72rem` (1152px)  
- `max-w-7xl` → `80rem` (1280px)  

---

### **Screen-Based Widths**  
- `max-w-screen-sm` → `640px`  
- `max-w-screen-md` → `768px`  
- `max-w-screen-lg` → `1024px`  
- `max-w-screen-xl` → `1280px`  
- `max-w-screen-2xl` → `1536px`  

---

### **Dynamic Widths**  
- `max-w-full` → `100%` (of parent container)  
- `max-w-min` → `min-content`  
- `max-w-max` → `max-content`  
- `max-w-fit` → `fit-content`  
- `max-w-prose` → Optimized for text readability (~65ch wide).  

---

### **Customization**  
Add your own values in `tailwind.config.js`:  
```js
module.exports = {
  theme: {
    extend: {
      maxWidth: {
        'custom': '90rem', // 1440px
      }
    }
  }
}
```
→ Use as `max-w-custom`.  

---

### **When to Use**  
- `max-w-xs` to `max-w-7xl`: Fixed-width containers (e.g., cards, modals).  
- `max-w-screen-*`: Responsive layouts tied to breakpoints.  
- `max-w-prose`: Blog posts, articles.  
- `max-w-full`: Allow full width but constrain child elements.  

Pair with `mx-auto` for centered layouts! 🎯
