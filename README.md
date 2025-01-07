# __IndieVesre__

## __Overview__
IndieVerse is a platform designed to connect indie game developers and players, fostering creativity and collaboration. It provides features for game publishing, player engagement, and an integrated marketplace for seamless game transactions. The platform is built using Spring Boot and MySQL, offering scalability and robust functionality.


## __Core Features__

Game Publishing: Developers can publish and manage their games.

Player Engagement: Players can buy games, add them to wishlists, and submit reviews (including video reviews).

Pre-Orders: Players can pre-order games, and activation codes are automatically sent on the release date.

Discount Management: Discounts can be dynamically applied or removed by the admin.

Game Analytics: Tracks downloads, purchases, and other key metrics.

Revenue Tracking: Total earnings from game sales are calculated dynamically.


## __Tech Stack__

Backend: Spring Boot

Database: MySQL

Security: Spring Security for authentication and user management

Email Notifications: Automated emails for transactions and pre-orders

Real-Time Scheduling: Quartz Scheduler for tasks like sending activation codes

Integration: SteamDB API (planned)

# __عالم الإندي__

## __نظرة عامة__

إندي فيرس هي منصة مصممة لربط مطوري الألعاب المستقلة مع اللاعبين، مما يعزز الإبداع والتعاون. توفر المنصة ميزات لنشر الألعاب، وتفاعل اللاعبين، وسوق متكامل لتسهيل معاملات الألعاب. تم بناء المنصة باستخدام Spring Boot وMySQL، مما يضمن القابلية للتوسع والوظائف القوية.

## __الميزات الأساسية__

نشر الألعاب: يمكن للمطورين نشر ألعابهم وإدارتها.

تفاعل اللاعبين: يمكن للاعبين شراء الألعاب، إضافتها إلى قوائم الرغبات، وتقديم مراجعات (بما في ذلك المراجعات بالفيديو).

الطلب المسبق: يمكن للاعبين طلب الألعاب مسبقًا، ويتم إرسال رموز التفعيل تلقائيًا في تاريخ الإصدار.

إدارة الخصومات: يمكن للإدارة تطبيق الخصومات أو إزالتها ديناميكيًا.

تحليلات الألعاب: تتبع التنزيلات، المشتريات، والمقاييس الرئيسية الأخرى.

تتبع الإيرادات: يتم حساب إجمالي الأرباح من مبيعات الألعاب ديناميكيًا.

## __التقنيات المستخدمة__

الواجهة الخلفية: Spring Boot

قاعدة البيانات: MySQL

الأمان: Spring Security لإدارة المصادقة والمستخدمين

إشعارات البريد الإلكتروني: رسائل بريد إلكتروني تلقائية للمعاملات والطلبات المسبقة

الجدولة في الوقت الحقيقي: Quartz Scheduler لمهام مثل إرسال رموز التفعيل

إضافة فديو وصوره : add image and video in databasee

رسم بياني :ClassDigram-->luced.app
رسم بياني :UsseeCase -->drow.io

التكامل: SteamDB API (مخطط له)

## __Links__

[Final Project on Figma](https://www.figma.com/design/fmij8RUf5p3tRiZtyWHFnP/Final-Project?node-id=187-7034&t=QkyWdXbZEsiK2saG-1)

[Presentaion](https://www.canva.com/design/DAGbZ_0Urrs/qAYvQk4ngNszlmng_w_j0A/edit?utm_content=DAGbZ_0Urrs&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

[Api Documentation](https://documenter.getpostman.com/view/39709985/2sAYJAcwS9)


![Api_Documentation](https://github.com/user-attachments/assets/ef8ea83c-e84e-492c-ac94-0b40fa869569)

## __Diagrams__

<img width="855" alt="IndieVerse_UseCase" src="https://github.com/user-attachments/assets/178a6cf4-ed11-4436-8a3a-b2cc6f85e49b" />

<img width="697" alt="IndieVerse_UseCase2" src="https://github.com/user-attachments/assets/699f550b-f032-46d7-9f8f-6d8535450fff" />


![IndieVerse_ClassDiagram](https://github.com/user-attachments/assets/4e66a1fa-87e0-4aed-b69b-36f1d6116961)


## __Endpoints Done By Me__

I have done the Models , DTOs , Service , Controller And CRUD for (Image ,admin)

AuthService , imageService ,imageRepository 

1- getReleasingGameRequests

2-getUnvalidatedDevelopers

3-getAllRequests

4-  getUnvalidatedReviewers

5-validateGame

6- validateSupportTicket

7- validateDeveloper

8- validateReviewer

9- banPlayer

10-unbanPlayer

11-banDeveloper

12-unbanDeveloper

13- banReviewer

14-banReviewer

15-unbanReviewer

16- uploadVideo

17-getVideo


