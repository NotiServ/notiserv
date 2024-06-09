# notiserv

## System Design
![NotificationPlatform drawio](https://github.com/NotiServ/notiserv/assets/121743571/4f7c7468-1841-45e3-aa8d-d68a837a8d20)



## Database Design (ERD)
![NotificationServiceDatabaseSchema drawio](https://github.com/NotiServ/notiserv/assets/121743571/5fd681b4-3add-402e-8c49-528d4ee7f05a)


- Tech Stack
    1. Flask
    2. PostgreSQL
    3. Cassandra
    4. Redis
    5. NextJS (Documentation)
    6. Docker
    7. Kubernetes
    8. Jenkins (CI/CD)

    
- Features
    1. Email APIs
    2. SMS APIs
    3. Whatapp APIs
    4. Push Notification APIs
    5. Custom Templates
    6. Bulk Send
    7. Subscription Based Model


- Service Details
    1. Email service: Based on SMTP server with custom email of organization.
    2. SMS Service: Use Fastsms api for now
    3. Whatsapp Service: Use Whataspp APIs
    4. Push Notifications: provide code in Java, Kotlin, Dart, swift, React Native and JavaScript


- APIs
    1. Authentication
        1. signup → username, email, phone, organization name, password, confirm password
        2. login → email, password
        3. forget password → email
        4. forget password → phone
        5. verify email → email, otp
        6. verify phone → phone, otp
        7. rest password → email, otp, new password, confirm new password

      
