# Ephemeris 1940-2027  
**Precision Ephemeris for Human Design & Astrology (0:00 UTC / Manual Calculation Edition)**

## I. Determine the Time with Known Longitude and Date (Example: 1948/4/9)
- **Start longitude** = 19.05037034°
- **End longitude** = 20.03243950°
- **Target longitude (Ra's at birth)** = 19.258380772°

### Calculation Steps:
1. **Total change** = 20.03243950 − 19.05037034 = `0.98206916°`
2. **Distance to known longitude** = 19.258380772 − 19.05037034 = `0.208010432°`
3. **Fraction** = 0.208010432 / 0.98206916 = `0.21183307`
4. **Time passed** = 0.21183307 × 24 = `5.0839937 hours`
5. **Convert decimal to H:M:S**:
   - Hours = `5`
   - Minutes = 0.0839937 × 60 = `5.039622` → `5 minutes`
   - Seconds = 0.039622 × 60 = `2.37732 seconds`
   
**Result:** `5:05:02` UTC

---

## II. Determine the Longitude with Known Time and Date (Example: 2025/1/21)
- **Start longitude** = 301.1871332°
- **End longitude** = 302.2046426°
- **Target time** = 19:10:23

### Calculation Steps:
1. **Longitude difference** = 302.2046426 − 301.1871332 = `1.0175094°`
2. **Convert time to decimal**:
   - 19 + (10/60) + (23/3600) = `19.1730556 hours`
3. **Fraction of 24-hour period** = 19.1730556 / 24 = `0.7988773`
4. **Longitude covered** = 1.0175094° × 0.7988773 = `0.812729°`
5. **Final longitude** = 301.1871332° + 0.812729° = `302.0008622°`

**Result:** `302.0008622°` at 19:10:23 UTC
