# Scaffolding  
I scaffolded the project using ```bash npx create-expo-app@latest ```  and then installing the dependencies using ```bash npm install ```
Then i ran into a problem as the codes were highlighted in red, the cause being that`--jsx ` compiler option isn't enabled in the 'compillerOptions' in tsconfig.json file.  
I downloaded the Expo Go app on my android device and ran the ```bash npx expo start ```, scanned the QR code and the app is running perfectly.  

## Reset Project Command  
After i ran the ```bash npm run reset-project ``` command, i was asked if i want to move the existing files to a new directory **/app-example** instead of deleting and after i selected yes, it created the directory and moved /app, /components, /hooks, /constants, /scripts into the new directory and created a new **/app** directory with app/index.tsx, app/_layout.tsx files.