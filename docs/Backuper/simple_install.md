# Simple Installation

## **Template Selection**

The first step in the simple installation is to select a template that matches your requirements. We offer three pre-defined templates:

- **Marzban**: Suitable for backing up Marzban panel data.
- **xui**: Designed for xui panel configurations.
- **Hiddify**: Tailored for Hiddify setups.

For example, if you are working with a Marzban panel, choose the **Marzban** template. This ensures that the backup is compatible with the specific data structures and settings of your panel.

## **Backup Name**

Assign a meaningful name to your backup process and file. This name helps you easily identify your backups later. For instance:

- **Master**
- **BackupPanel**

## **Cron Job Setup**

Specify how frequently you want the backup to run. Enter the interval in minutes. For example:

- **Every hour**: Enter `60`.
- **Every day**: Enter `1440` (which is 24 hours).

This allows you to automate your backups to fit your schedule.

## **Destination**

Choose where you want your backups to be sent. Backuper supports two platforms:

- **Telegram**
- **Discord**

### **Telegram Integration**

For sending backups to Telegram, you’ll need:

- **Bot Token**: This is an authentication token for your Telegram bot, which you can obtain by creating a bot on Telegram.
- **Chat ID**: A unique identifier for the Telegram chat where the backups will be sent.

### **Discord Integration**

For Discord, you will need:

- **Webhook URL**: This URL allows you to post messages to a specified Discord channel. You can generate this URL in the Discord server settings.

## **Completion**

Once you’ve configured these settings, your backup process will be set up and ready to start based on your chosen schedule. Remember to star the Backuper repository on GitHub to support ongoing development and improvements.
