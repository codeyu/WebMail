# webmail

## 常见邮箱(gmail/163/qq/outlook/live/hotmail/sina)邮件服务器(smtp/pop3/imap)地址和端口设置

smtp   用来发送邮件

pop3 、imap  为收取邮件

红色为建议选择，端口建议选择ssl加密的方法。

1.  163邮箱
```
POP3服务器: pop.163.com      110  995(ssl)
SMTP服务器: smtp.163.com     25   465(ssl)
IMAP服务器: imap.163.com     143  993(ssl)
```

2.  QQ邮箱
```
POP3服务器: pop.qq.com      110  995(ssl)
SMTP服务器: smtp.qq.com     25   465(ssl)
IMAP服务器: imap.qq.com     143 993(ssl)
```
3.  Outlook/Live/Hotmail邮箱
```
POP3服务器: pop-mail.outlook.com      110  995(ssl)
SMTP服务器: smtp-mail.outlook.com     25  587 465(ssl)
IMAP服务器: imap-mail.outlook.com     143  993(ssl)
【海外的smtp端口25不行的情况下建议使用587】
```
4.Gmail
```
POP3服务器: pop.gmail.com      110  995(ssl)
SMTP服务器: smtp.gmail.com      25  587 465(ssl)
IMAP服务器: imap.gmail.com     143  993(ssl)
【国内被封了 可能会需要各种fq工具辅助】
```
5. Sina.com
```
POP3服务器: pop.sina.com      110  995(ssl)
SMTP服务器: smtp.sina.com      25 587 465(ssl)
IMAP服务器: imap.sina.com      143 993(ssl)
```
**有些在使用前需要在服务商后台设置里选择开启smtp、pop3、imap后才能使用，如gmail、outlook**
