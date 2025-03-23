
## **🎨 UI (User Interface) Improvements**

### **1️⃣ Visual Hierarchy & Readability**
✅ **Increase Contrast** – Ensure text (especially on video backgrounds) is easily readable.  
✅ **Consistent Font Styling** – Use 2-3 font styles max; maintain uniform line spacing.  
✅ **Optimized Button Styles** –  
   - CTA buttons should have a **bold, contrasting color** (e.g., orange) to grab attention.  
   - Use **hover effects** (e.g., scale, shadow) for a more interactive feel.  

---

### **2️⃣ Layout & Design Consistency**
✅ **Spacing & Alignment:**  
   - Ensure equal **padding/margins** across sections for a clean look.  
   - Keep elements **centered & aligned** to avoid clutter.  

✅ **Responsive Design Check:**  
   - Ensure **perfect adaptability** on mobile screens.  
   - Optimize **navigation bar** for smaller screens (consider a sticky navbar).  

✅ **UI Animations & Microinteractions:**  
   - Add **subtle hover effects** to images, buttons, and cards.  
   - Smooth **fade-ins & scroll-based animations** (but avoid excessive motion).  

---

## **👨‍💻 UX (User Experience) Enhancements**

### **1️⃣ Improve Onboarding & Navigation**
✅ **Sticky Navigation Bar** – Helps users easily navigate sections.  
✅ **Clear Call-to-Actions (CTAs)** – Every section should have a purpose:  
   - Use **action-driven text** like *"Try EduAI Now"* instead of *"Learn More"*.  
✅ **Breadcrumbs or Progress Indicators** – If the site has multiple pages, show users where they are.  

---

### **2️⃣ User Flow & Accessibility**
✅ **Simplify Sign-Up Process** –  
   - Offer **Google login** for one-click access.  
   - Keep the signup form **short & intuitive** (avoid unnecessary fields).  

✅ **Optimize Load Times** –  
   - Reduce **video background size** for faster loading.  
   - Use **lazy loading** for images to improve speed.  

✅ **Accessibility Best Practices** –  
   - Ensure **keyboard navigation** works well.  
   - Add **alt text** for images & improve color contrast for visually impaired users.  

---
// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyCbTVfF8MrMsF2eeZYG4WQnI9sh3NmmEME",
  authDomain: "eduai-assistant.firebaseapp.com",
  projectId: "eduai-assistant",
  storageBucket: "eduai-assistant.firebasestorage.app",
  messagingSenderId: "234970951094",
  appId: "1:234970951094:web:529f578aaab09f9a95e517",
  measurementId: "G-BB2B8L2GMP"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);
