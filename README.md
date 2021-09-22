# StarGit
 create an application that uses Golang, Vue.js, Vue CLI, Vuetify, Okta etc to star favourite Git Repos
 
 
Uses an Okta account for Authentication and User Management, therefore currently on hold. Needs company credentials


Basic application that lets user star their fav Git Repos.
Created using Vue.js Vue CLI, Vuetify, Vuex, Golang, Okta etc.
Later use MongoDB to manage Data.


---------------------------------------------------------------------------------
Follow these steps:


yarn global add @vue/cli
choose yarn or npm as per requirement

npm install -g yarn

Create a vue app:
mkdir web
cd web 
vue create app

in case above line doesnt work (as in my case)
use --> npm install -g @vue/cli
and then ---> vue create app

Choose the default recommended options and then I selected NPM

cd app
npm run build
npm run serve

------------------------------------------------------------------------------------

Application will now be available on  http://localhost:8080 , Follow the link under terminal (Better to install Live Server under VS Code, that makes it even easier)

Make the application more responsive using Vuetify then

Vuetify is a collection of Vue.js components.
vue add vuetify
Choose default options

Vuetify provides out-of-the box features including a grid system, typography, basic layout, and also components like cards, dialogs, chips, tabs, icons and so on.
Build the application again and Run.

------------------------------------------------------------------------------

Now is the time to add Authentication via Okta
Add application there. Choose Single page application.

------------------------------------------------------------------------------
-------------------------------------------------------------------------------------

I am refering following link: 
https://developer.okta.com/blog/2018/10/23/build-a-single-page-app-with-go-and-vue

Thanks
Seema Singla
