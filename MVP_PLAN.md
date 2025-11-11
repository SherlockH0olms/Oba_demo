# OBA QR Data System - MVP PLAN

## Project Overview

**OBA QR Data System** is an AI-powered customer intelligence and digital marketplace platform for Azerbaijan's leading retail chain.

### Key Metrics
- **TAM (Total Addressable Market):** 21 billion AZN - General retail turnover
- **SAM (Serviceable Available Market):** 2.3 billion AZN - Digital transformation segment
- **SOM (Serviceable Obtainable Market):** 1.0-1.2 billion AZN - Realistic achievable revenue
- **Store Count:** 1600+ physical branches
- **Average Store Revenue:** 1-1.5 million AZN/year

---

## MVP Features

### Phase 1: Core Customer Management
- [x] Customer registration via QR code
- [x] Telegram bot integration
- [x] Customer profile management
- [x] Purchase history tracking

### Phase 2: Transaction & Loyalty
- [x] Transaction recording
- [x] Points system (1 AZN = 1 point)
- [x] Reward management
- [x] Loyalty tier system

### Phase 3: Analytics & Intelligence
- [x] Customer segmentation
- [x] Purchase analytics
- [x] Top products dashboard
- [x] Revenue insights

### Phase 4: Integration
- [x] Telegram Bot API
- [x] QR Code generation
- [x] Real-time notifications

---

## Technical Stack

### Backend
- **Framework:** FastAPI (Python)
- **Database:** PostgreSQL
- **Cache:** Redis
- **Authentication:** JWT
- **Task Queue:** Celery

### Frontend
- **Framework:** React 18
- **Build Tool:** Vite
- **Styling:** Tailwind CSS
- **State:** Zustand

### Integration
- **Telegram Bot:** pyTelegramBotAPI
- **QR Code:** qrcode library
- **Analytics:** Pandas, NumPy

---

## Project Structure

```
Oba_demo/
├── backend/
│   ├── main.py
│   ├── database.py
│   ├── models.py
│   ├── schemas.py
│   ├── crud.py
│   ├── routes/
│   ├── services/
│   ├── telegram_bot.py
│   └── requirements.txt
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── vite.config.js
├── docs/
│   ├── MVP_PLAN.md
│   ├── INSTALLATION.md
│   └── API_DOCS.md
└── README.md
```

---

## MVP Implementation Timeline

**Week 1: Backend Setup**
- Database schema design
- FastAPI project initialization
- Basic CRUD operations

**Week 2: Customer Management**
- Customer registration endpoints
- Profile management
- QR code generation

**Week 3: Loyalty System**
- Points calculation
- Reward management
- Transaction tracking

**Week 4: Frontend & Integration**
- React dashboard
- Telegram bot integration
- Analytics endpoints

**Week 5: Testing & Deployment**
- Unit tests
- Integration tests
- Docker deployment

---

## Success Metrics

- Customer registration rate: 1000+ users/week
- Average transaction tracking accuracy: 99%+
- API response time: <200ms
- System uptime: 99.9%
- Daily active users: 10,000+

---

## Next Steps

1. Set up backend infrastructure
2. Implement core APIs
3. Build frontend dashboard
4. Integrate Telegram bot
5. Deploy to production
