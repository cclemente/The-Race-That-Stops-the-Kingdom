# 🏇 The Race That Stops the Kingdom
*What if the Melbourne Cup was open to every land animal on Earth?*

This repository explores the biomechanics of speed and endurance across species — using the **Critical Speed (CS)** model to predict how long each animal would take to complete the **3,200 m Melbourne Cup**.

---

## 📐 The Model

The **critical speed (CS)** framework describes the relationship between sustainable speed, finite sprint capacity, and time:

$$
t = \frac{D - D'}{CS}
$$

where:  
- **t** = time to cover the distance (s)  
- **D** = race distance (3,200 m)  
- **CS** = *critical speed* (m/s), the highest sustainable pace  
- **D'** = *distance reserve* (m), the finite distance that can be run above CS before fatigue sets in  

---

## 🏁 Benchmark

- **Melbourne Cup distance:** 3,200 m  
- **Record winning time:** 3:16.3 min (1990, *Kingston Rule*)  
- **Average speed:** 16.3 m/s (58.7 km/h)

---

## 🧍‍♂️ Humans

**Parameters**  
- CS = 5.83 m/s (men), 5.33 m/s (women)  
- D' = 287 m (Burnley 2023)

**Calculations**

$$
t_{men} = \frac{3200 - 287}{5.83} = 499 s = 8 min 19 s
$$

$$
t_{women} = \frac{3200 - 287}{5.33} = 546 s = 9 min 06 s
$$

**Summary**  
Elite by track standards, but far behind the horses.

**Refs:**  
Burnley M. (2023) *Comparative Biochemistry and Physiology A*, 279: 111387.  
Jones et al. (2021) *J. Appl. Physiol.*, 130(2): 369–379.  
World Athletics (2023) marathon records.

---

## 🦩 Ostrich

**Parameters**  
- CS = 4.35 m/s (preferred speed, Daley 2016)  
- Max speed = 11.3 m/s (Rubenson 2011)  
- Hold time = 120 s  

$$
D' = (11.3 - 4.35) \times 120 = 834 m
$$
$$
t = \frac{3200 - 834}{4.35} = 544 s = 9 min 05 s
$$

**Refs:**  
Rubenson et al. (2011) *J. R. Soc. Interface*, 8: 740–755.  
Daley et al. (2016) *J. Exp. Biol.*, 219: 3301–3308.  
Alexander et al. (1979) *J. Zool.*, 187: 169–178.

---

## 🐆 Cheetah

**Parameters**  
- Longest hunt ≈ 500 m (Wilson 2013)  
- Mean speed = 15 m/s  
- Duration ≈ 33 s  
- D' ≈ 330 m  
- Solve for CS:
  $$
  CS = \frac{500 - 330}{33} ≈ 5.1 m/s
  $$
$$
t = \frac{3200 - 330}{5.1} = 563 s = 9 min 23 s
$$

**Refs:**  
Wilson et al. (2013) *Nature*, 498: 185–189.

---

## 🦘 Kangaroo

**Parameters**  
- CS = 6.5 m/s (Dawson & Taylor 1973)  
- Max speed ≈ 17 m/s (Wikipedia estimates)  
- Hold = 60 s  

$$
D' = (17 - 6.5) \times 60 = 630 m
$$
$$
t = \frac{3200 - 630}{6.5} = 395 s = 6 min 35 s
$$

**Refs:**  
Dawson & Taylor (1973) *Nature*, 246: 313–314.  
Thornton et al. (2025) *eLife*, doi: 10.7554/eLife.96437.2.

---

## 🐕 Greyhound

**Parameters**  
- Based on 715 m (41.23 s) and 943 m (60.18 s) “stayer” records  
- Solving \(v = CS + D'/t\) → **CS ≈ 12.0 m/s**, **D' ≈ 219 m**

$$
t = \frac{3200 - 219}{12.0} = 248 s = 4 min 07 s
$$

**Refs:**  
Rose et al. (1991) *Res. Vet. Sci.*, 50: 355–361.  
Larsson & Sjöström (1992) *J. Small Anim. Pract.*, 33: 604–610.

---

## 🦓 Zebra

**Parameters**  
- vₘₐₓ ≈ 15 m/s  
- CS ≈ 6.0 m/s (Wilson 2018)  
- Hold ≈ 30 s  

$$
D' = (15 - 6) \times 30 = 270 m
$$
$$
t = \frac{3200 - 270}{6.0} = 488 s = 8 min 08 s
$$

**Refs:**  
Wilson et al. (2018) *Nature*, 554: 183–188.

---

## 🦌 Pronghorn Antelope

**Parameters**  
- vₘₐₓ = 24.6 m/s (55 mph)  
- CS ≈ 8.0 m/s (estimated sustained pace)  
- Hold ≈ 20 s  

$$
D' = (24.6 - 8.0) \times 20 = 332 m
$$
$$
t = \frac{3200 - 332}{8.0} = 359 s = 5 min 59 s
$$

**Refs:**  
NPS.gov (2023) *Pronghorn factsheet*.  
Wikipedia (“Pronghorn”).  

---

## 🏆 Results Summary

| Species | CS (m/s) | D' (m) | Predicted Time (s) | Time (min:s) |
|----------|-----------|--------|--------------------|---------------|
| Horse (*record*) | 16.3 | — | 196 | 3:16 |
| Greyhound | 12.0 | 219 | 248 | 4:07 |
| Pronghorn | 8.0 | 332 | 359 | 5:59 |
| Kangaroo | 6.5 | 630 | 395 | 6:35 |
| Zebra | 6.0 | 270 | 488 | 8:08 |
| Human (male) | 5.83 | 287 | 499 | 8:19 |
| Ostrich | 4.35 | 834 | 544 | 9:05 |
| Cheetah | 5.1 | 330 | 563 | 9:23 |

---

## 📊 Conclusion

The science is clear — **thoroughbreds** dominate endurance speed.  
Greyhounds and pronghorns are the only serious challengers, while kangaroos make the podium on efficiency.  
Behind them, zebras, humans, ostriches, and even cheetahs cross the line minutes later — proving that the Melbourne Cup truly is the **race that stops the kingdom.**
