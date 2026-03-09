# EdFlow

Modern school management & administration platform designed for Ghanaian schools.

## Core Features (MVP Goals)
- Role-based dashboards: Admin, Teacher, Parent, Student
- Daily attendance (QR code + manual marking)
- Continuous assessment, grades & report cards
- Fee collection with MTN MoMo / Vodafone Cash via Paystack
- Lightweight AI insights (early warnings for at-risk students)
- Mobile-first experience + offline support

## Tech Stack
- **Frontend**: Flutter (Dart) – Android, iOS, Web
- **Backend**: Node.js + Express + Sequelize ORM + MySQL
- **Payments**: Paystack (MoMo, cards)
- **Theme**: Light beige (#F8F1E9) + teal accents (#00A896) + subtle Ghanaian kente elements
- **Auth**: JWT + role-based access control

## Folder Structure (planned)

edflow/
├── backend/          # Node.js/Express API
│   ├── src/
│   │   ├── config/
│   │   ├── controllers/
│   │   ├── middlewares/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── services/
│   │   └── utils/
│   ├── server.js
│   └── package.json
├── frontend/         # Flutter mobile/web app
│   ├── lib/
│   ├── pubspec.yaml
│   └── ...
├── docs/             # Designs, wireframes, API docs, screenshots
└── README.md
