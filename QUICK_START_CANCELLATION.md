# 🎯 Quick Start Guide - Appointment Cancellation

## How to Cancel an Appointment

You now have **3 different ways** to cancel an appointment. Choose the one that's most convenient for you!

---

## 📍 Method 1: From My Appointments List

**Best for:** Quickly canceling from your appointments overview

### Steps:
1. **Navigate** to "My Appointments" page
2. **Find** the appointment you want to cancel in the table
3. **Look** for the "Cancel" button in the last column (Update Booking)
4. **Click** the "Cancel" button
5. **Review** the appointment details in the confirmation modal
6. **Click** "Yes, Cancel Appointment" to confirm

### What You'll See:
```
┌─────────────────────────────────────────────────────────┐
│  My All Appointments                                    │
├─────┬──────────┬──────┬────────┬─────────┬─────────────┤
│ SNO │   Date   │ FEES │ Status │ Penalty │   Actions   │
├─────┼──────────┼──────┼────────┼─────────┼─────────────┤
│  1  │ 16-02-26 │ 500  │pending │    -    │ [Cancel]    │ ← Click here
└─────┴──────────┴──────┴────────┴─────────┴─────────────┘
```

---

## 📍 Method 2: From Appointment Details Page

**Best for:** When you're reviewing appointment details

### Steps:
1. **Navigate** to "My Appointments" page
2. **Click** "details" link for any appointment
3. **Look** for the "Cancel Appointment" button in the header
4. **Click** the "Cancel Appointment" button
5. **Review** the appointment details in the confirmation modal
6. **Click** "Yes, Cancel Appointment" to confirm

### What You'll See:
```
┌──────────────────────────────────────────────────────────┐
│  Your Appointment Details                                │
│                                                           │
│  [Download Bill]  [Cancel Appointment]  [GO BACK]        │
│                        ↑                                  │
│                   Click here                              │
│                                                           │
│  Doctor Name: Dr. John Smith                             │
│  Booking Date: 16-02-2026                                │
│  ...                                                      │
└──────────────────────────────────────────────────────────┘
```

---

## 📍 Method 3: Right After Booking (Payment Success)

**Best for:** If you change your mind immediately after booking

### Steps:
1. **Complete** payment for an appointment
2. **Wait** for the payment success page to load
3. **Click** "Cancel This Appointment" button
4. **Review** the appointment details in the confirmation modal
5. **Click** "Yes, Cancel Appointment" to confirm

### What You'll See:
```
┌──────────────────────────────────────────────────────────┐
│                                                           │
│           Payment Successful! 🎉                         │
│                                                           │
│  ✓ Your appointment has been successfully confirmed.     │
│                                                           │
│  [View My Appointments]  [Cancel This Appointment]       │
│                                    ↑                      │
│                               Click here                  │
└──────────────────────────────────────────────────────────┘
```

---

## 🎨 The Confirmation Modal

When you click any cancel button, you'll see this beautiful modal:

```
┌─────────────────────────────────────────────────────────┐
│  ⚠️ Cancel Appointment                              [×] │ ← Purple gradient header
├─────────────────────────────────────────────────────────┤
│                                                          │
│  Are you sure you want to cancel this appointment?      │
│                                                          │
│  ┌────────────────────────────────────────────────┐    │
│  │ Appointment Details:                           │    │
│  │ Doctor:  Dr. John Smith                        │    │
│  │ Date:    16-02-2026                            │    │
│  │ Time:    10:00:00 AM                           │    │
│  │ Amount:  ₹500                                  │    │
│  └────────────────────────────────────────────────┘    │
│                                                          │
│  ┌────────────────────────────────────────────────┐    │
│  │ ⚠️  Important: If you cancel within 2 hours   │    │ ← Yellow warning
│  │     of your appointment time, a penalty of     │    │
│  │     50% of the booking amount will be applied. │    │
│  └────────────────────────────────────────────────┘    │
│                                                          │
├─────────────────────────────────────────────────────────┤
│                 [Keep Appointment]  [Yes, Cancel]       │ ← Clear action buttons
└─────────────────────────────────────────────────────────┘
```

---

## ⚠️ Important: Penalty Information

### When is a penalty applied?

**50% penalty** is charged if you cancel:
- ✅ **Within 2 hours** of your appointment time
- ✅ The penalty is **automatically calculated** by the system

### When is NO penalty applied?

**No penalty** if you cancel:
- ✅ **More than 2 hours** before your appointment time
- ✅ You'll get a **full refund**

### Example:
```
Appointment Time: 16-02-2026 at 2:00 PM
Appointment Fee: ₹500

Cancel at 11:00 AM (3 hours before) → No penalty, full refund
Cancel at 1:00 PM (1 hour before)  → 50% penalty = ₹250 charged
```

---

## 📧 Email Notification

After cancellation, you'll receive an email with:
- ✅ Confirmation of cancellation
- ✅ Appointment details
- ✅ Penalty information (if applicable)
- ✅ Booking ID for reference

---

## ❌ When Can't You Cancel?

The cancel button will **NOT appear** for:
- ❌ Already **canceled** appointments
- ❌ **Paid** appointments (completed with payment)
- ❌ Appointments that have **already passed**

You'll see "Closed" instead of the cancel button for these.

---

## 🔒 Safety Features

### Accidental Click Prevention
- ✅ Confirmation modal prevents accidental cancellations
- ✅ Clear "Keep Appointment" button to back out
- ✅ Click outside modal to close without canceling

### Clear Information
- ✅ All appointment details shown before confirming
- ✅ Penalty warning clearly displayed
- ✅ Two-step process (click cancel → confirm in modal)

---

## 💡 Tips

1. **Review carefully** - Check all details in the modal before confirming
2. **Watch the time** - Cancel early to avoid penalties
3. **Check your email** - Confirmation will be sent to your registered email
4. **Keep booking ID** - Save the booking ID from the email for reference

---

## 🆘 Need Help?

If you have any issues:
1. Check that you're logged in
2. Verify the appointment status is "pending" or "unpaid"
3. Try refreshing the page
4. Contact support with your booking ID

---

## ✅ Summary

| Method | Best For | Steps |
|--------|----------|-------|
| **My Appointments List** | Quick cancellation | 1. Go to My Appointments<br>2. Click Cancel button<br>3. Confirm |
| **Appointment Details** | Detailed review | 1. Open appointment details<br>2. Click Cancel Appointment<br>3. Confirm |
| **After Payment** | Immediate change of mind | 1. On success page<br>2. Click Cancel This Appointment<br>3. Confirm |

**All methods are safe, easy, and include penalty warnings!** ✨

---

*Last updated: February 16, 2026*
