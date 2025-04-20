# ✅ SLCM Feedback Auto-Filler (Yes to All)

Tired of manually clicking “Yes” for every feedback question on the SLCM portal? This quick and easy JavaScript trick will help you auto-fill all responses in seconds.

---

## 🚀 How to Use

1. Open the SLCM feedback form in your browser
2. Press `F12` or `Ctrl + Shift + I` to open **Developer Tools**
3. Go to the **Console** tab
4. Paste the following code and press Enter:

```javascript
document.querySelectorAll('input[type="radio"][value="Yes"]').forEach(r => r.click());
