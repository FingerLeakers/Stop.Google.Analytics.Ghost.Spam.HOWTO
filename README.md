<img src="https://github.com/mitchellkrogza/Stop.Google.Analytics.Ghost.Spam.HOWTO/blob/master/.assets/stop-google-analytics-ghost-spam.png" alt="How to Stop Google Analytics Ghost Spam using a well curated list of spam referrer domains and web sites"/><img src="https://github.com/mitchellkrogza/Stop.Google.Analytics.Ghost.Spam.HOWTO/blob/master/.assets/spacer.jpg"/>[![DUB](https://img.shields.io/dub/l/vibe-d.svg)](https://github.com/mitchellkrogza/Stop.Google.Analytics.Ghost.Spam.HOWTO/blob/master/LICENSE.md)<img src="https://github.com/mitchellkrogza/Stop.Google.Analytics.Ghost.Spam.HOWTO/blob/master/.assets/spacer.jpg"/>[![GitHub release](https://img.shields.io/github/release/mitchellkrogza/Stop.Google.Analytics.Ghost.Spam.HOWTO.svg)](https://github.com/mitchellkrogza/Stop.Google.Analytics.Ghost.Spam.HOWTO/releases/latest)<img src="https://github.com/mitchellkrogza/Stop.Google.Analytics.Ghost.Spam.HOWTO/blob/master/.assets/spacer.jpg"/>[![Build Status](https://travis-ci.org/mitchellkrogza/Stop.Google.Analytics.Ghost.Spam.HOWTO.svg?branch=master)](https://travis-ci.org/mitchellkrogza/Stop.Google.Analytics.Ghost.Spam.HOWTO)<img src="https://github.com/mitchellkrogza/Stop.Google.Analytics.Ghost.Spam.HOWTO/blob/master/.assets/spacer.jpg"/><a href='https://twitter.com/ubuntu101za'><img src='https://img.shields.io/twitter/follow/ubuntu101za.svg?style=social&label=Follow' alt='Follow @ubuntu101za'></a>

# HOW TO Stop Google Analytics "Ghost" Spam

**How to stop Google Analytics "Ghost" Spam using a well curated list of spam referrer domains and web sites. Simple and easy to use with visual instructions for creating Segments in Google Analytics using my google-exclude files.**

_______________
#### Version: V1.2017.7
#### Bad Referrer Count: 
```

Status      Percentage   Numbers     
----------- ------------ -------------
ACTIVE      98%          5391        
INACTIVE    1%           59          
INVALID     0%           0           
```
____________________

- Created by: https://github.com/mitchellkrogza
- Copyright Mitchell Krog <mitchellkrog@gmail.com>

### If this helps you [why not buy me a beer](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=BKF9XT6WHATLG):beer:

# What is "Ghost" Spam?

Spam in Google Analytics (GA) is becoming a serious issue. Due to a deluge of referral spam from social buttons, adult sites, and many, many other sources, people are starting to become overwhelmed by all the filters they are setting up to manage the useless data they are receiving. Referrer spam produces corrupt analytics data and on many sites a good 70% of what you may be seeing as hits to your sites are actually spam referral traffic. 

They are called ghosts because they never access your site. As unusual as it sounds, this type of spam doesn't have any interaction with your site at all. You may wonder how that is possible since one of the main purposes of GA is to track visits to our sites. They do it by using the Measurement Protocol, which allows people to send data directly to Google Analytics' servers. Using this method, and probably randomly generated tracking codes (UA-XXXXX-1) as well, the spammers leave a "visit" with fake data, without even knowing who they are hitting.

# Instructions to stop "Ghost" Spam on On Analytics

Follow the simple step by step visual instructions below to add these google-exclude files as segments to your web site.

<table style="width:100%;margin:0;">
  <tr>
    <td align="left"><img src="https://github.com/mitchellkrogza/Stop.Google.Analytics.Ghost.Spam.HOWTO/blob/master/.assets/google-analytics-ghost-spam-01.jpg" alt="Google Analytics - Adding Segments to Stop Ghost Spam"/></td>
  </tr>
  <tr>
    <td align="left"><img src="https://github.com/mitchellkrogza/Stop.Google.Analytics.Ghost.Spam.HOWTO/blob/master/.assets/google-analytics-ghost-spam-02.jpg" alt="Google Analytics - Adding Segments to Stop Ghost Spam"/></td>
  </tr>
  <tr>
    <td align="left"><img src="https://github.com/mitchellkrogza/Stop.Google.Analytics.Ghost.Spam.HOWTO/blob/master/.assets/google-analytics-ghost-spam-03.jpg" alt="Google Analytics - Adding Segments to Stop Ghost Spam"/></td>
  </tr>
  <tr>
    <td align="left"><img src="https://github.com/mitchellkrogza/Stop.Google.Analytics.Ghost.Spam.HOWTO/blob/master/.assets/google-analytics-ghost-spam-04.jpg" alt="Google Analytics - Adding Segments to Stop Ghost Spam"/></td>
  </tr>
  <tr>
    <td align="left"><img src="https://github.com/mitchellkrogza/Stop.Google.Analytics.Ghost.Spam.HOWTO/blob/master/.assets/google-analytics-ghost-spam-05.jpg" alt="Google Analytics - Adding Segments to Stop Ghost Spam"/></td>
  </tr>
  <tr>
    <td align="left"><img src="https://github.com/mitchellkrogza/Stop.Google.Analytics.Ghost.Spam.HOWTO/blob/master/.assets/google-analytics-ghost-spam-06.jpg" alt="Google Analytics - Adding Segments to Stop Ghost Spam"/></td>
  </tr>
  <tr>
    <td align="left"><img src="https://github.com/mitchellkrogza/Stop.Google.Analytics.Ghost.Spam.HOWTO/blob/master/.assets/google-analytics-ghost-spam-07.jpg" alt="Google Analytics - Adding Segments to Stop Ghost Spam"/></td>
  </tr>
</table>    

## The Information Sources

The referrer domains contained in this repository comes from over a year's worth of curation from my <a href="https://github.com/mitchellkrogza/nginx-ultimate-bad-bot-blocker">Nginx Referrer Spam and Bot Blocker</a> and <a href="https://github.com/mitchellkrogza/apache-ultimate-bad-bot-blocker">Apache Referrer Spam and Bot Blocker</a> Projects. These lists are carefully moderated and curated and also constantly updated.


### Some cool free projects

- https://github.com/mitchellkrogza/nginx-ultimate-bad-bot-blocker
- https://github.com/mitchellkrogza/apache-ultimate-bad-bot-blocker
- https://github.com/mitchellkrogza/Badd-Boyz-Hosts
- https://github.com/mitchellkrogza/fail2ban-useful-scripts
- https://github.com/mitchellkrogza/linux-server-administration-scripts
- https://github.com/mitchellkrogza/Travis-CI-Nginx-for-Testing-Nginx-Configuration
- https://github.com/mitchellkrogza/Travis-CI-for-Apache-For-Testing-Apache-and-PHP-Configurations
- https://github.com/mitchellkrogza/Fail2Ban-Blacklist-JAIL-for-Repeat-Offenders-with-Perma-Extended-Banning
- https://github.com/funilrys/funceble
- https://github.com/mitchellkrogza/The-Big-List-of-Hacked-Malware-Web-Sites

### Into Photography?

Come drop by and visit me at https://mitchellkrog.com or <a href='https://twitter.com/MitchellKrog'><img src='https://img.shields.io/twitter/follow/MitchellKrog.svg?style=social&label=Follow' alt='Follow @MitchellKrog'></a>

### Coding makes me very thirsty [why not buy me a beer](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=BKF9XT6WHATLG):beer:
