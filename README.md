 Serverless Order Management System

מערכת ניהול הזמנות serverless מבוססת ארכיטקטורת אירועים הבנויה על AWS, עם יכולות ניתוח תמונות AI.

סקירה כללית

פרויקט המדגים ארכיטקטורת ענן מתקדמת, עיבוד אסינכרוני, ואינטגרציית AI/ML עם Amazon Rekognition.

תכונות עיקריות

- ניהול הזמנות מלא
- התראות דוא"ל אוטומטיות
- גיבוי אוטומטי
- דוחות PDF
- ניתוח תמונות AI
- ממשק web responsive

שירותי AWS

Lambda, API Gateway, DynamoDB, S3, SNS, Rekognition, Amplify, CloudWatch

API Endpoints

Base URL: https://6kav3jqnbg.execute-api.us-east-1.amazonaws.com/prod

- POST /orders
- GET /orders
- GET /orders/{id}
- PUT /orders/{id}
- DELETE /orders/{id}
- POST /notifications/subscribe
- POST /notifications/unsubscribe
- GET /reports
- POST /orders/{id}/analyze-image

Amazon Rekognition לניתוח אוטומטי של תמונות מוצרים - זיהוי אובייקטים וחילוץ טקסט.

מבנה הפרויקט

serverless-order-management/
├── docs/           תיעוד מלא
├── lambda/         קוד Functions
├── web-client/     אפליקציית Web
└── screenshots/    צילומי מסך

תיעוד
תיעוד מפורט זמין בתיקיית docs.

סטטיסטיקות

- Lambda Functions: 11
- API Endpoints: 9
- שירותי AWS: 7+
- שורות קוד: כ-2,500

נבנה עם AWS Serverless https://github.com/Nofarhal/serverless-order-management

