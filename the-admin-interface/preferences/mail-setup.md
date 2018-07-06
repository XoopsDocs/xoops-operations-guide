# Mail Setup

This section of the control panel is used to configure your email for the system. It is recommended that you leave the Mail Delivery Method on the default setting “PHP \(mail\)”. You do not need to fill in the Sendmail or SMTP fields unless you use an alternative mail delivery option.

| Field | Description |
| --- | --- |
| FROM address | Enter the email address you want to use for administrative purposes |
| FROM name | This is the name that will be used when you send mail |
| FROM user | When the system sends a private message to a user, you can choose whom it appears to have been sent from here. |
| Mail delivery method | Choose the method used to deliver mail here. The default is “PHP \(mail\)”. It is recommended that you do not change this unless you experience problems.The other options available are i\) Sendmail; ii\) SMTP; iii\) SMTPAuth. |
| Path to sendmail | Enter the path to the sendmail program \(or substitute\) on the webserver here \(only if you use this mail delivery option\). The default is “/usr/sbin/sendmail” |
| SMTP host\(s\) | Enter a list of SMTP servers to try to connect to here \(only if you use SMTP, otherwise leave it blank\) |
| SMTPAuth username | Enter your username to connect to an SMTP host with SMTPAuth here \(only if you use this mail delivery option, otherwise leave it blank\). |
| SMTPAuth password | Enter your password to connect to an SMTP host with SMTPAuth \(only if you use this mail delivery option, otherwise leave it blank\) |

