# ROOTED Experiences — UI Front-End QA Requirements

Experiences is safety-critical and location-sensitive.

Backend authority ALWAYS wins.

---

## 1. Discovery UI

MUST:
- Enforce radius <= 50 miles  
- Enforce 25 marker limit  
- Use 6–8 card rows  
- Rotate results from backend only  

MUST NOT:
- Highlight risky adventures to minors  
- Introduce algorithmic rankings  

---

## 2. Experience Profiles

Show:
- Difficulty rating  
- Safety requirements  
- What to bring  
- Photos / videos  
- Age recommendations  

Hide:
- Adult-only waivers in Kids Mode  
- Pricing in Kids Mode  

---

## 3. Map UI

- Adventure landmarks  
- Parks & trails  
- Waterways  
- Seasonal overlays  

Kids Mode map shows:
- ONLY nature walks  
- ONLY educational safe zones  

---

## 4. Events UI

Experience events must clearly show:
- Safety level  
- Age minimum  
- Weather implications  

Kids Mode hides:
- High-risk activities  
- Solo adventures  

---

END OF QA