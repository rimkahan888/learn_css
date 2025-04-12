### **CSS 80/20 Priority List**

1. **Box Model**  
   - `width/height`, `padding`, `border`, `margin`  
   - `box-sizing: border-box`

2. **Display Types**  
   - `block`, `inline`, `flex`, `grid`

3. **Flexbox Essentials**  
   - `display: flex`  
   - `justify-content` (main axis)  
   - `align-items` (cross axis)  
   - `gap` for spacing

4. **CSS Grid Basics**  
   - `grid-template-columns` with `fr` units  
   - `gap` for spacing

5. **Positioning**  
   - `relative` + `absolute` combo  
   - `fixed` for sticky elements  
   - `sticky` for scroll effects

6. **Responsive Design**  
   - Mobile-first media queries  
   - `min-width` breakpoints

7. **Specificity Hierarchy**  
   - Classes > IDs > Elements  
   - Avoid `!important`

8. **CSS Variables**  
   - `:root { --color: red }`  
   - `var(--color)`

9. **Pseudo-Classes/Elements**  
   - `:hover`, `:nth-child()`  
   - `::before`, `::after`

10. **Debugging Shortcut**  
    - `* { outline: 1px solid red; }`

**Pro Tip:** Master Flexbox + Box Model first – they solve ~70% of layout problems. Then add Grid for complex 2D layouts.
