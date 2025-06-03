# 📌 Plugin Update & Maintenance Status

Thanks for your interest in my Ren'Py tools. 

I'm currently focused on job applications, so responses and updates may be slower than usual.  

- **Update Window**: Active updates will begin in 2–3 months, after I finish my job search.
- **Past Inactivity**: Limited support in the past year due to personal reasons  
- **Renewed Focus**: Recent dev work clarified solutions to key issues

If you run into any problems, feel free to DM me on Discord (**san0901**) —  
I'll do my best to help.

---

### 🔧 Planned Plugin Updates (v1.02 ~ v2.x)  

> 📅 Expected: **Sep–Dec 2025**

I'm aiming to improve all tools for **latest Ren'Py compatibility** and **simpler usability**.  
This includes rebuilding internals with custom `Displayable` classes while keeping usage clean and minimal.  
Recent practice has made this approach feasible — updates will focus on clarity and ease of use.

#### 🎙️ 1. Lip Sync Tool  
- **v1.02**
  - Fix class inheritance conflicts (switch to native base class)  
  - Simplified call structure (may require manual audio filename input)
- **v1.03**
  - Automation: Sync with Excel or visual interface (graphic viewer)

#### 🖼️ 2. Layout Tool  
- **v1.02**
  - Alpha/zoom control  
  - Clipboard copy for coordinates  
  - Built-in support for custom transitions (hover/active)
- **v2.01**
  - UI for transition preview/add  
  - Support for stacked/smooth transitions (`onhide`, `onshow`, ATL)

#### 🎮 3. Interactive Game Plugin  
- **Problem**: Python logic breaks Ren'Py rollback  
- **Planned Fix**:  
  - Refactor using screen language + timer-based flow, **or**  
  - Build v2 with custom `renpy.Displayable` class for better rollback compatibility

#### 🔘 4. RadioButton Group Plugin  
- **Priority**: High  
- **Goals**:  
  - Easier flag handling  
  - Customizable options  
  - Usable without deep Python/Ren'Py knowledge  
  - Out-of-the-box examples
