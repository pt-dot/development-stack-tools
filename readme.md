# DOT Indonesia Development Stack & Tools

Ini adalah panduan tentang development stack dan perangkat saja yang perlu dipasang di masing-masing PC untuk kebutuhan development DOT Indonesia di masing-masing divisi.

Kunjungi [DOT Stacks (Stackshare.io)](https://stackshare.io/dot-indonesia/stack) untuk mengetahui stack dan layanan yang kami gunakan. 

---

## General

+ [Xmind - Mindmap](https://www.xmind.net/)
+ [Slack](https://slack.com/)
+ [Trello - Task Organizer](https://trello.com/)
+ [Gitlab Repository](https://gitlab.com)
+ [Google Drive](https://drive.google.com) - document management
+ [Git](https://git-scm.com/) - Distributed version control
+ [SourceTree](https://www.sourcetreeapp.com/), [Gitkraken](https://www.gitkraken.com/) - Git client
+ [iTerm](https://www.iterm2.com/) - Terminal replacement untuk MacOS dan dapat diintegrasikan dengan [Z-Shell](https://ohmyz.sh/) agar lebih interaktif
+ [Homebrew](https://brew.sh/) - Package manager untuk macOS
+ [Spotify](https://www.spotify.com/id/) - Pemutar musik online (jangan lupa bahagia :D)
+ [Gitscrum](https://site.gitscrum.com) - Scrum / Agile Project management
---

## Backend dan Frontend

### Development Stacks

+ PHP >= 7.1
+ Apache 2.4 - Open source web server
+ MySQL >= 5.6 - Relational Database Management System
+ [Nodejs (LTS)](https://nodejs.org/en/download/)
+ [NPM](https://www.npmjs.com/), [Yarn](https://yarnpkg.com/en/), [Composer](https://getcomposer.org/) - Package Manager
+ [Laravel Server Requirement](https://laravel.com/docs/master#server-requirements)
+ [Postman](https://www.getpostman.com/) - API Development & testing environment
+ [Putty](https://www.putty.org/) - ssh client windows

#### Frontend
+ [Webpack](https://webpack.js.org/) - Static module bundler
+ [Bower](https://bower.io/) - web package manager
+ [Sass](https://sass-lang.com/), [Less](http://lesscss.org/) - CSS Preprocessor
+ [Vue CLI](https://github.com/vuejs/vue-cli) - Standard vue development tool
+ [Create react app](https://github.com/facebook/create-react-app) - create react app with no build configuration
+ [Vue Dev Tools](https://github.com/vuejs/vue-devtools) - browser devtools extension untuk development menggunakan vue
+ [Gulp](https://gulpjs.com/)

#### Opsional:

+ [Nginx](https://www.nginx.com/) - Web server, load balancer, & reverse proxy
+ [Docker](https://docs.docker.com/)
+ [Laravel Homestead](https://laravel.com/docs/5.6/homestead) - Development environment yang berbasis vagrant untuk aplikasi PHP atau laravel
+ [Virtual Box](https://www.virtualbox.org/wiki/Downloads) - Virtual box dibutuhkan untuk host laravel homestead
+ [Vagrant](https://www.vagrantup.com/downloads.html) - Development environment untuk laravel homestead
+ [Laravel Valet](https://laravel.com/docs/5.6/valet) - Laravel environment khusus untuk Mac
+ [MongoDB Database](https://www.mongodb.com/) - NoSQL database
+ [Robomongo](https://robomongo.org/) - Native mongodb management
+ [Redis](https://redis.io/) atau via [Redis Docker Image](https://hub.docker.com/_/redis/) - In Memory database
+ [Kitematic](https://kitematic.com/) atau [Portainer](https://portainer.io/) - GUI Docker Management
+ [Memchached](https://memcached.org/) - Open source memory object caching system
+ [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-2017) - Microsoft SQL Server Database
+ [MySQL WorkBench](https://www.mysql.com/products/workbench/) - Perangkat visual untuk perancangan, reverse engineering database MySQL
+ [PHPMyAdmin](https://www.phpmyadmin.net/) - Web based MySQL database management
+ [Sequel Pro](https://www.sequelpro.com/) - MySQL Database management for Mac
+ [PHP Coding Standards Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer)
+ [Google Cloud SDK](https://cloud.google.com/sdk/) - Perangkat untuk mengelola Google Cloud Platform

### Tools & IDE

+ Free Editor: [Visual Studio Code](https://code.visualstudio.com/), [Sublime Text](https://www.sublimetext.com/) (Freemium), [vim](https://www.vim.org/)
+ Non Free Editor: [PhpStorm](https://www.jetbrains.com/phpstorm/), [WebStorm](https://www.jetbrains.com/webstorm/)

---


## Mobile

### Development Stacks

#### iOS

+ Cocoapods
+ Swift 4+
+ Use Design Pattern [MVVM](https://github.com/balitax/MVVM-AC-Template)


### Tools & IDE (iOS)

+ [Xcode](https://developer.apple.com/xcode/)

#### Android
+ Android Minimal SDK Support 16
+ Android Target SDK Support --> Latest SDK
+ Kotlin
+ Use Programming Pattern [MVVM](https://github.com/pt-dot/DOT-Kotlin-Boilerplate)
+ [Android Architecture Components](https://developer.android.com/topic/libraries/architecture/)

### Tools & IDE (Android)
+ [Android Studio](https://developer.android.com/studio/)
+ [Genymotion](https://www.genymotion.com/)

### Deployment
+ [Genymotion](https://www.genymotion.com/)
+ [deploygate](https://deploygate.com/)
---

## Quality Assurance Engineering

### Development Stacks

+ [Postman](https://www.getpostman.com/) API Development & testing environment
+ [Newman](https://github.com/postmanlabs/newman) Automation for postman collection
+ [Codeception](https://codeception.com/) Automated test : unit, API, functional
+ [Laravel Dusk](https://github.com/laravel/dusk) Automated browser test for Laravel
+ [Selenium](https://www.seleniumhq.org/) Automated browser test
+ [Firebase Test Lab](https://firebase.google.com/docs/test-lab/) Mobile device testing
+ [Sentry.io](https://sentry.io/) Error reporting
+ [Google Page Speed](https://developers.google.com/speed/pagespeed/insights/), [Lighthouse](https://developers.google.com/web/tools/lighthouse/) Page speed test

### Tools & IDE

+ [Postman Dekstop / Postman Chrome Extension](https://www.getpostman.com/)
+ [Katalon](https://www.katalon.com/)
+ [JMeter](https://jmeter.apache.org/)
+ [Sublime Text](https://www.sublimetext.com/)
+ [Jenkins](https://jenkins.io/)

### Documents

+ User Story
+ Test Scenario / Test Case
+ Manual Book
+ UAT Documents
+ TSD
+ BSD

---

## Design

### Tools

+ [Sketch](https://www.sketchapp.com/) - UI UX Design Toolkit
+ [Adobe XD](https://www.adobe.com/sea/products/xd.html) - UI UX Design toolkit
+ [Balsamiq](https://balsamiq.com/) - Wireframing tools
+ [Draw.io](https://www.draw.io/) - online design untuk diagram
+ [miro](https://miro.com/) - visual collaboration platform (mindmap, agile, lean, customer journey map, dll)
+ [Invision](https://www.invisionapp.com/) - Kolaborasi design
+ [Zeplin](https://zeplin.io/) - Kolaborasi asset design
+ [Figma](https://www.figma.com) - UI UX Design Toolkit (Free)
+ [Adobe XD](https://www.adobe.com/sea/products/xd.html) - UI UX Design Toolkit
+ [Adobe Photoshop](https://www.adobe.com/sea/products/photoshop.html) - Design / Photo manipulation

---

# Panduan Kontribusi

Internal engineer silakan berkontribusi untuk membuat guideline ini bisa lebih lengkap dan lebih baik. Caranya:

+ Fork repository ini
+ Buat branch baru di repository hasil fork
+ Edit file readme sesuai dengan kebutuhan lalu commit.
+ Ajukan pull request
+ AVP divisi atau VP of engineering akan melakukan review dan melakukan approval Pull Request.

Jika ada pertanyaan atau permintaan update silakan untuk mengajukan [issue](https://github.com/pt-dot/development-stack-tools/issues) di repository terkait.
