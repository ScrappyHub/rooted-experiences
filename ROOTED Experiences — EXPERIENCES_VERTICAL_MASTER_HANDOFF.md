# ROOTED Experiences — Master Handoff (UI + Backend Alignment)

Status: Documentation-complete  
Scope: Experiences vertical UI  
Backend: Events + Landmarks + Providers + Seasonal Engine  

If app behavior conflicts with this → this document wins.

---

## 1. Vertical Definition

ROOTED Experiences includes:

- Outdoor recreation  
- Guided adventures  
- Tourism activities  
- Nature learning  
- Seasonal outdoor events  

It is:

✅ Educational-friendly  
❌ Not adrenaline-first  
❌ Not an Airbnb Experience clone  

---

## 2. Roles & Access

### Guest
May browse experiences.

### Individual
May join events, save experiences.

### Vendors
Outdoor vendors may host:

- Guided tours  
- Classes  
- Rentals  
- Camps  

Vendors cannot:
- Message minors  
- List age-restricted activities to minors  

### Institutions
Used mainly for:
- Field trips  
- Group recreation  
- Nature education  

### Admin
Moderates safety, experience approvals, seasonal overlays.

---

## 3. Kids Mode

Kids Mode must filter out:

❌ Ziplining  
❌ Rock climbing  
❌ Whitewater rafting  
❌ Anything requiring waivers  

Kids Mode may show:
- Nature walks  
- Birdwatching  
- Educational tours  
- Parks  

---

## 4. Seasonal Overlays

Experiences inherits seasonal intelligence from ROOTED Core:

- Heat advisories  
- Flood risks  
- Winter hazards  
- Wildlife alerts  

Kids Mode removes hazard overlays entirely.

---

## 5. Event Types

Uses ROOTED Core `events` with:

- event_type = 'experience'  
- event_vertical = 'EXPERIENCES'  

---

## 6. Launch Checklist

- Experience discovery  
- Outdoor vendor filtering  
- Safe event posting  
- Kids Mode overlays  
- Seasonal advisories  

---

END OF HANDOFF