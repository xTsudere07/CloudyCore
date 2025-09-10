# 📘 BÀI TẬP ĐẠO HÀM
> Từ dễ đến khó - Công thức toán học rõ ràng với LaTeX

---

## 📋 Mục lục
- [1. Bài tập dễ](#1-bài-tập-dễ)
- [2. Bài tập trung bình](#2-bài-tập-trung-bình) 
- [3. Bài tập khó](#3-bài-tập-khó)
- [4. Bài tập nâng cao](#4-bài-tập-nâng-cao)
- [5. Bài tập ứng dụng](#5-bài-tập-ứng-dụng)

---

## 1. Bài tập dễ

### 🔍 **Công thức cần nhớ**

| Hàm số | Đạo hàm | Ghi chú |
|--------|---------|---------|
| $x^a$ | $ax^{a-1}$ | Công thức lũy thừa |
| $\sqrt{x}$ | $\frac{1}{2\sqrt{x}}$ | Căn bậc hai |
| $\frac{1}{x}$ | $-\frac{1}{x^2}$ | Phân số |
| $\sin x$ | $\cos x$ | Hàm lượng giác |
| $\cos x$ | $-\sin x$ | Hàm lượng giác |

### 📝 **Bài tập thực hành**

#### **Bài 1**
**Đề bài:** Tính $f'(x)$ với $f(x) = x^3 + 2x$

> 💡 **Áp dụng:** $(x^a)' = ax^{a-1}$

<details>
<summary>🔎 Xem lời giải</summary>

$$f'(x) = (x^3)' + (2x)'$$
$$= 3x^2 + 2$$

</details>

---

#### **Bài 2** 
**Đề bài:** Tính $y'$ với $y = \sqrt{x} + \frac{1}{x}$

> 💡 **Áp dụng:** $(\sqrt{x})' = \frac{1}{2\sqrt{x}}$ và $\left(\frac{1}{x}\right)' = -\frac{1}{x^2}$

<details>
<summary>🔎 Xem lời giải</summary>

$$y' = (\sqrt{x})' + \left(\frac{1}{x}\right)'$$
$$= \frac{1}{2\sqrt{x}} + \left(-\frac{1}{x^2}\right)$$
$$= \frac{1}{2\sqrt{x}} - \frac{1}{x^2}$$

</details>

---

#### **Bài 3**
**Đề bài:** Tính $y'$ với $y = 5x^4 - 7x + 9$

> 💡 **Áp dụng:** $(x^a)' = ax^{a-1}$ và $(c)' = 0$

<details>
<summary>🔎 Xem lời giải</summary>

$$y' = (5x^4)' - (7x)' + (9)'$$
$$= 5 \cdot 4x^3 - 7 \cdot 1 + 0$$
$$= 20x^3 - 7$$

</details>

---

#### **Bài 4**
**Đề bài:** Tính $y'$ với $y = \sin x + \cos x$

> 💡 **Áp dụng:** $(\sin x)' = \cos x$ và $(\cos x)' = -\sin x$

---

#### **Bài 5**
**Đề bài:** Tính $y'$ với $y = x^2 + \sqrt{x} + \frac{1}{x}$

> 💡 **Áp dụng:** $(x^a)'$, $(\sqrt{x})'$, $\left(\frac{1}{x}\right)'$

---

## 2. Bài tập trung bình

### 🔍 **Công thức hàm hợp**

| Hàm hợp | Đạo hàm | Ghi chú |
|---------|---------|---------|
| $u^a$ | $au^{a-1} \cdot u'$ | Lũy thừa hàm hợp |
| $\sin u$ | $u' \cos u$ | Sin hàm hợp |
| $\cos u$ | $-u' \sin u$ | Cos hàm hợp |
| $\sqrt{u}$ | $\frac{u'}{2\sqrt{u}}$ | Căn hàm hợp |

### 📝 **Bài tập thực hành**

#### **Bài 6**
**Đề bài:** Tính $y'$ với $y = (3x^2 + 1)^5$

> 💡 **Áp dụng:** $(u^a)' = au^{a-1} \cdot u'$ với $u = 3x^2 + 1$

<details>
<summary>🔎 Xem lời giải</summary>

Đặt $u = 3x^2 + 1 \Rightarrow u' = 6x$

$$y' = 5u^4 \cdot u'$$
$$= 5(3x^2 + 1)^4 \cdot 6x$$
$$= 30x(3x^2 + 1)^4$$

</details>

---

#### **Bài 7**
**Đề bài:** Tính $y'$ với $y = \sin(2x + 3)$

> 💡 **Áp dụng:** $(\sin u)' = u' \cos u$ với $u = 2x + 3$

<details>
<summary>🔎 Xem lời giải</summary>

Đặt $u = 2x + 3 \Rightarrow u' = 2$

$$y' = u' \cos u$$
$$= 2 \cos(2x + 3)$$

</details>

---

#### **Bài 8**
**Đề bài:** Tính $y'$ với $y = \cos(x^2)$

> 💡 **Áp dụng:** $(\cos u)' = -u' \sin u$ với $u = x^2$

---

#### **Bài 9**
**Đề bài:** Tính $y'$ với $y = \sqrt{x^2 + 1}$

> 💡 **Áp dụng:** $(\sqrt{u})' = \frac{u'}{2\sqrt{u}}$ với $u = x^2 + 1$

---

## 3. Bài tập khó

### 🔍 **Công thức tích và thương**

| Loại | Công thức | Ghi chú |
|------|-----------|---------|
| **Tích** | $(uv)' = u'v + uv'$ | Quy tắc Leibniz |
| **Thương** | $\left(\frac{u}{v}\right)' = \frac{u'v - uv'}{v^2}$ | Quy tắc thương |

### 📝 **Bài tập thực hành**

#### **Bài 10** 
**Đề bài:** Tính $y'$ với $y = (x^2 + 1)(x^3 - 2x)$

> 💡 **Áp dụng:** $(uv)' = u'v + uv'$

<details>
<summary>🔎 Xem lời giải</summary>

Đặt:
- $u = x^2 + 1 \Rightarrow u' = 2x$
- $v = x^3 - 2x \Rightarrow v' = 3x^2 - 2$

$$y' = u'v + uv'$$
$$= 2x(x^3 - 2x) + (x^2 + 1)(3x^2 - 2)$$
$$= 2x^4 - 4x^2 + 3x^4 + 3x^2 - 2x^2 - 2$$
$$= 5x^4 - 3x^2 - 2$$

</details>

---

#### **Bài 11**
**Đề bài:** Tính $y'$ với $y = \frac{x^2 + 3x + 2}{x + 1}$

> 💡 **Áp dụng:** $\left(\frac{u}{v}\right)' = \frac{u'v - uv'}{v^2}$

<details>
<summary>🔎 Xem lời giải</summary>

Đặt:
- $u = x^2 + 3x + 2 \Rightarrow u' = 2x + 3$
- $v = x + 1 \Rightarrow v' = 1$

$$y' = \frac{u'v - uv'}{v^2}$$
$$= \frac{(2x + 3)(x + 1) - (x^2 + 3x + 2) \cdot 1}{(x + 1)^2}$$
$$= \frac{2x^2 + 2x + 3x + 3 - x^2 - 3x - 2}{(x + 1)^2}$$
$$= \frac{x^2 + 2x + 1}{(x + 1)^2} = \frac{(x + 1)^2}{(x + 1)^2} = 1$$

</details>

---

#### **Bài 12**
**Đề bài:** Tính $y'$ với $y = \frac{2x + 1}{x^2 + 1}$

> 💡 **Áp dụng:** $\left(\frac{u}{v}\right)' = \frac{u'v - uv'}{v^2}$

---

#### **Bài 13**
**Đề bài:** Tính $y'$ với $y = (x^3 + 1)\sqrt{x}$

> 💡 **Áp dụng:** $(uv)' = u'v + uv'$

---

## 4. Bài tập nâng cao

### 🔍 **Công thức hàm mũ và logarit**

| Hàm số | Đạo hàm | Ghi chú |
|--------|---------|---------|
| $e^u$ | $u' \cdot e^u$ | Hàm mũ tự nhiên |
| $a^x$ | $a^x \ln a$ | Hàm mũ cơ số a |
| $\ln u$ | $\frac{u'}{u}$ | Logarit tự nhiên |
| $\log_a u$ | $\frac{u'}{u \ln a}$ | Logarit cơ số a |

### 📝 **Bài tập thực hành**

#### **Bài 14**
**Đề bài:** Tính $y'$ với $y = e^{2x^2}$

> 💡 **Áp dụng:** $(e^u)' = u' \cdot e^u$ với $u = 2x^2$

<details>
<summary>🔎 Xem lời giải</summary>

Đặt $u = 2x^2 \Rightarrow u' = 4x$

$$y' = u' \cdot e^u$$
$$= 4x \cdot e^{2x^2}$$

</details>

---

#### **Bài 15**
**Đề bài:** Tính $y'$ với $y = \ln(3x^2 + 1)$

> 💡 **Áp dụng:** $(\ln u)' = \frac{u'}{u}$ với $u = 3x^2 + 1$

---

#### **Bài 16**
**Đề bài:** Tính $y'$ với $y = 2^x$

> 💡 **Áp dụng:** $(a^x)' = a^x \ln a$ với $a = 2$

---

#### **Bài 17**
**Đề bài:** Tính $y'$ với $y = \ln(\sin x)$

> 💡 **Áp dụng:** $(\ln u)' = \frac{u'}{u}$ với $u = \sin x$

---

## 5. Bài tập ứng dụng

### 🔍 **Ứng dụng vật lý**

| Khái niệm | Công thức | Ý nghĩa |
|-----------|-----------|---------|
| **Vận tốc tức thời** | $v(t) = s'(t)$ | Đạo hàm của quãng đường |
| **Gia tốc tức thời** | $a(t) = v'(t) = s''(t)$ | Đạo hàm của vận tốc |

### 📝 **Bài tập thực hành**

#### **Bài 18**
**Đề bài:** Một vật có quãng đường $s(t) = 5t^2 + 3t$. Tính vận tốc tức thời tại $t = 2$.

> 💡 **Áp dụng:** $v(t) = s'(t)$

<details>
<summary>🔎 Xem lời giải</summary>

$$v(t) = s'(t) = (5t^2 + 3t)'$$
$$= 10t + 3$$

Tại $t = 2$:
$$v(2) = 10(2) + 3 = 23 \text{ (đơn vị vận tốc)}$$

</details>

---

#### **Bài 19**
**Đề bài:** Một vật có vận tốc $v(t) = 6t - 4$. Tính gia tốc tức thời.

> 💡 **Áp dụng:** $a(t) = v'(t)$

---

#### **Bài 20**
**Đề bài:** Một vật có quãng đường $s(t) = t^3 - 3t^2 + 2t$. Tính vận tốc tại $t = 1$ và $t = 3$.

> 💡 **Áp dụng:** $v(t) = s'(t)$

---

## 🎯 **Lời khuyên học tập**

> ⭐ **Bí quyết:** Làm từ dễ đến khó, nắm vững công thức cơ bản trước
> 
> ⭐ **Lưu ý:** Luôn kiểm tra kết quả bằng cách thay số cụ thể
> 
> ⭐ **Thực hành:** Mỗi ngày 5-10 bài để thành thạo

---

## 📚 **Tài liệu tham khảo**

- [Khan Academy - Calculus](https://www.khanacademy.org/math/calculus-1)
- [Paul's Online Math Notes](https://tutorial.math.lamar.edu/Classes/CalcI/CalcI.aspx)
- Sách giáo khoa Giải tích 12

---

*📚 Được soạn với ❤️ - Chúc bạn học tốt!*

**⭐ Nếu tài liệu hữu ích, hãy cho repo một ngôi sao nhé!**
