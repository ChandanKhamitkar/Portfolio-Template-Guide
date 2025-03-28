# Portfolio-Template-Guide
A detailed editable information of portfolio template.

# ❓ Want to modify template according to your relevance!

### ✉️ **Change the `top most` mail?**
    - Go to `\src\app\components\navbar\Navbar.tsx`
    - Edit **line 5** to update your email.

### 🏷️ **Rename Large Name Section, Description & Availability Status**?
    - Go to `\src\app\components\hero\Hero.tsx`

### **🔗 Update `Social Links`**
    - Go to `\src\app\components\connect\ConnectSocial.tsx`
    - And modify links in 👇
        ```
        const connectInfo = [
                {
                    id : 1,
                    imgLink : '/logos/github_icon_white.png',
                    link : 'https://github.com/ChandanKhamitkar',
                    name : 'Github'
                },
                {
                    id : 2,
                    imgLink : '/logos/twitter_icon_white.png',
                    link : 'https://twitter.com/chandan_k_dev',
                    name : 'Twitter'
                },
                {
                    id : 3,
                    imgLink : '/logos/linkedin_icon_white.png',
                    link : 'https://www.linkedin.com/in/chandankhamitkar/',
                    name : 'LinkedIn'
                },
            ];
        ```

### **🛠️ Modify the `Projects Section`?**
    - Edit in `\src\utils\experienceInfo.ts`
    - and edits will be reflected automatically
    - and for project images, make sure to add it in `/public/images`

### **🖥️ Edit `Technical Skills`?**
    - Navigate to `\src\app\components\techSkills\TechSkills.tsx`

### **📄 Update Your `Resume`?**
    - upload your updated resume in `\public\docs`
    - update file name in `\src\app\components\hireme\HireMe.tsx`
    - lookup at `line no: 15 ( for resume )`
    - update `mail in line no: 10`

### **🎓 Modify the `Experience Section`?**
    - Go to `\src\utils\experienceInfo.ts`

### **📬 `Enable Portfolio Contact` Form Emails?**
    - create a `apikey` in `web3forms`
    - update it with `line no: 14`
