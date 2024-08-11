# Advanced Installation

## **Template Selection**

Just like in the simple installation, select a template from the following options:

- **Marzban**
- **xui**
- **Hiddify**
- **Custom**: For users who need to create a tailored template.

## **Customization**

The advanced installation allows you to specify which files and directories should be included or excluded from the backup. For example:

- **Include**: `/home/user/important_files/`
- **Exclude**: `/tmp/` or any temporary directories.

This customization ensures that only the necessary data is backed up, optimizing storage and backup efficiency.

## **Backup Name**

Provide a descriptive name for your backup process. Examples include:

- **Master**
- **BackupPanel**

## **Cron Job Configuration**

Set how often the backup should be performed by entering the interval in minutes. Examples include:

- **Daily at Midnight**: Enter `1440` minutes (24 hours).
- **Weekly**: Enter `10080` minutes (7 days).

## **Caption**

Optionally, add a caption to describe the backup’s contents or purpose. This can help with documentation and tracking. If not needed, you can skip this step by pressing Enter.

## **Compression Type**

Choose the compression format for your backup. We support two formats:

- **ZIP**: A popular and widely-compatible format that is easy to use. ZIP files can be opened by most operating systems and archive utilities. It is suitable for general backup needs and is well-supported across different platforms.
  
- **7z**: Known for a higher compression ratio and more efficient data compression compared to ZIP. This format is ideal for larger backups where space efficiency is important. However, 7z files may require specific software (like 7-Zip) to open, which might not be as universally available as ZIP utilities.

## **Destination**

Select the platform for sending your backups:

- **Telegram**
- **Discord**

### **Telegram Integration**

You will need:

- **Bot Token**: Obtain this token by creating a Telegram bot.
- **Chat ID**: Find this in your Telegram chat or group settings.

### **Discord Integration**

You will need:

- **Webhook URL**: Create this URL through Discord server settings.

## **Completion**

Your advanced backup configuration is complete. The backup process will follow the schedule and settings you’ve defined. Be sure to star the Backuper repository on GitHub to support ongoing development and enhancements.
