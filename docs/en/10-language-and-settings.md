# 10. Settings: language and Gemini key

Pick the language, enter a Gemini key and choose a model.

**Prerequisites:** For the key: a Google AI Studio account.

## Steps

1. Open **Settings**. Paste the key into **Gemini API key** (**Show** reveals it) or use **Scan the key from a QR code**, pick a **Model** and tap **Save key**. The first time you save a key an alert asks you to agree to sending photos to Google. **Test connection** checks the key and model. How to get a key is described below.

   ![Settings: language and Gemini key – 1](../../media/10-language-and-settings/en-01-settings.png)

2. The **Model** menu lists the defaults, and **Add your own model…** lets you type your own model name.

   ![Settings: language and Gemini key – 2](../../media/10-language-and-settings/en-02-model.png)

3. **Clear key** removes the key and your agreement. **Help and guide** opens this guide in the browser.

## Result

Without a key the app works with the offline labels only. The key is stored only on the phone, in the iOS Keychain, and a backup does not move it to another device.

## How to get a Gemini key

Open [aistudio.google.com/api-keys](https://aistudio.google.com/api-keys) in a browser. Any browser works (Chrome, Firefox, Edge, Safari), on the phone or on a computer. The key is a long string that starts with `AIza`. It is free and needs no bank card. If you have used Google AI Studio before, you land straight on the list of keys.

### You are not signed in to Google (or you do not use Chrome)

1. The page sends you to a sign-in. Enter the email and password of your personal Google account (Gmail). If you have none, create one with "Create account".
2. If the browser is not Chrome, nothing changes: you sign in on Google's page, not in the browser.
3. On first visit a terms-of-service dialog appears. Tick and accept it, otherwise the page does not continue.

### You have more than one account

1. Look at the round icon (photo or letter) in the top right. It shows which account you are signed in with.
2. If it is not the one you want, tap the icon and pick another account or "Add another account".
3. If the browser keeps signing you in with the wrong (for example work) account, open the page in an incognito/private window and sign in only with the account you want.
4. Work and school accounts (Google Workspace) are often blocked by the administrator. Use a personal account.
5. Keys belong to an account. A key created with one account is not visible from another.

### You have no key: create one

1. On the **API keys** page tap **Create API key**.
2. It asks for a Google Cloud project. If you already have one, pick it from the list. If not, choose to create a new project. The name does not matter.
3. The key appears in the list. Copy it (the copy icon next to the key, or open the key and copy it there).
4. If you see a message that there are no projects, first choose the option to create or import a project, then repeat step 1.

### You already have a key: where to find it

1. The same **API keys** list shows all keys of the account, with name, project and creation date.
2. Tap the key's row to see the whole key and copy it. If only part is shown (`AIza...xxxx`), open its details.
3. No keys listed? Most likely you are signed in with a different account. Switch it (see above). If the key is really gone or you do not remember where it is, create a new one; the old one does no harm.
4. Do not share the key or show it in screenshots. Whoever has it uses your quota.

### How to put it in the app

- On the phone: copy the key, open **Settings** in the app, paste it and tap **Save key**.
- On a computer: send the key to yourself (for example in a message to yourself) and copy it on the phone, or show it as a QR code and scan it from the app.
- Finally tap **Test connection**. A green result means the key works.


---

[← Previous](09-apple-health.md) · [Back to contents](../../README.md#contents)
