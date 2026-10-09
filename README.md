# Signals & Systems bot — student usage guide

This repository is **student help only** (not source code). If you just opened the Telegram bot, read this page, then register.

The same guide is also available in Persian: [HELP.md](./HELP.md).

---

## 1. What you need

1. A Telegram account (the same one you opened the bot with)
2. Your **student ID** (`student_id` from the TA, e.g. `ST01`)
3. Your **6-digit PIN**, given by the TA out of band — not in the class group chat

Do not share your PIN in the group or with classmates.

---

## 2. Register (first time)

In the bot chat, send:

```text
/register <student_id> <pin>
```

Example:

```text
/register ST01 123456
```

- Put a space between the ID and the PIN.
- If you get an error, check both values and try again carefully.
- Each student ID binds to **one** Telegram account. If it is already bound to another account, contact the TA.

After a successful registration you can open assignments.

---

## 3. View assignments

Two ways:

### A) Telegram command

```text
/weeks
```

You will see published weeks, deadlines, and how many attempts you have left.

### B) Mini App

Open the in-Telegram Mini App from the bot menu or the button the TA set up. There you can:

- pick a week
- read the questions and open figures / data files
- enter answers and submit

Do not open the app in a normal browser tab; it must be opened **from inside Telegram**.

---

## 4. Submit answers

1. Open the week’s assignment.
2. Enter each answer as described in the question (number, sequence, etc.).
3. Submit. You usually have several **attempts**; the best score is kept.
4. After the deadline, submissions close unless the TA extended yours.

If you see a “not registered” message, run `/register` again or send `/start`.

---

## 5. Useful commands

| Command | Purpose |
| --- | --- |
| `/start` | Welcome / start |
| `/register <id> <pin>` | Bind your Telegram account to your student ID |
| `/weeks` | List published assignments |

---

## 6. Common problems

**“That student ID and PIN do not match”**  
Wrong ID or PIN, or too many failed tries and a temporary lock. Wait a few minutes or ask the TA to unlock you.

**“Already registered on another device”**  
This student ID is bound to a different Telegram account. Only the TA can move it.

**Mini App won’t open / session error**  
Open it from inside the bot in Telegram, not a copied link in Chrome. If it still fails, close the bot and send `/start` again.

**Past the deadline**  
Submission is closed. Contact the TA if you have a valid reason for an extension.

---

## 7. Important notes

- The PIN is your login secret — do not post it publicly.
- Reference answers are personalized per student; copying a classmate’s answers usually fails grading.
- This guide only explains **how to use the bot**, not how to solve the homework.

---

## 8. Contact

For registration issues, PIN lockouts, or moving your Telegram account, message the **course TA** and include your student ID (do not send your PIN in a public chat).
