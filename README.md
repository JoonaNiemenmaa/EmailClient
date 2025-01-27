# Android Email Client

This is a working SMTP and IMAP client accompanied by an android application for sending / displaying internet mail messages.

The application is designed to work with a sandboxed local mail server and is not meant to be used to send / receive emails via the internet.

## Usage

This application is designed to work with the Greenmail mail server. It provides a suite of sandboxed mail servers for testing / development use.

Install the Greenmail .jar file from their [website]([url](https://greenmail-mail-test.github.io/greenmail/#about)).

You also need [Android Studio]([url](https://developer.android.com/studio)) so that you can run the app via its emulator.

Now run the Greenmail .jar executable with the following command:

```console
foo@bar:~$ java -Dgreenmail.setup.test.smtp -Dgreenmail.setup.test.imap \
     -Dgreenmail.users=test1:pwd1 -jar greenmail-standalone.jar
```
Now you can run the app via Android Studio and use the app. You can log in with username test1 and password pwd1

## Pictures

Login screen

![image](https://github.com/user-attachments/assets/dae97c8c-3622-4d54-8352-0351a4a64915)

Displaying mail

![image](https://github.com/user-attachments/assets/b525c102-f228-495c-9421-f0d1372cc4fa)

Composing a mail message

![image](https://github.com/user-attachments/assets/2049b736-d59d-407b-a36d-79144971dc3d)

Examining a mail message

![image](https://github.com/user-attachments/assets/8621c9d0-e641-4ba6-8051-7457f26f3e9e)

