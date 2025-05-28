---
title: Automation hackers broke It ain't broke, don't fix it
type:  articles
datePublished: 2023-03-21
date: 2023-03-21
header:
 overlay_image: /assets/images/SafetyCabinet.png
 caption: Safety strap - when forklift meets electronics - "Ain't broke"​. - Credit Teresa Butner and the Infrastructure Team

excerpt: Risk management in automation used to center around productivity and financial risks, but a new risk has emerged ... hackers..

---

Risk management in automation used to center around productivity and financial risks, but a new risk has emerged ... hackers.

## My journey of awareness?

As a developer and a purchaser of automation tools and systems, our security teams started asking lots and lots of questions about our automation products.
That led me to ask vendors about security and for certain security related tasks during pricing.
You'd be amazed at the answers and lack of answers.

Then our vendor partner, Tompkins Robotics, invited me to the #promat2023 panel discussion around risk, triggering me to put my thoughts on paper to bring this to your attention.

## How automation developed a new risk

## Automation evolution

Classical automation like conveyor, diverters, lifters and transporters are built to execute a fixed feature set all day every day without fail.
Older embedded control systems were purpose built with flashed ROM and simple electronics. They were connected to each other, but not connected to the world. Your biggest risks in automation were up-time and outages were physical or electrical.

Moores law combined with device hobbyism created a new breed of more sophisticated automation at lower cost.
These systems have powerful processors and chips in them and can execute complicated logic.

Now the kicker. To add features and send data, we connected them .... to EVERYTHING.
 With connectivity comes bad actors and this is where the landscape changed.

## The security economy

 Hackers used to work for a challenge, for a cause or for targeted espionage.
 Now hacking and extortion is a viable business model. Hackers powered the economy of protectors and detectors. Kind of like Star Wars good versus evil, but everyone gets paid. Those with exposure buy insurance increasing the likelihood of people getting paid. All these factors combine in a positive growth cycle for the security economy.

 Recent increases in attacks means more payouts resulting in insurance companies increasing rates to reduce risk. Either reduce your risk or pay a higher rate, if you can even get insurance for your exposure level.

## Weakness in the fortressAutomation is the new weakness in the fortress. They cant get in through the front-door so now they are exploring the fringes and this means automation.

 Automations primary risk was outage, so the primary design goal was repeatability and stability. There was little demand for features or data. Engineers built the code, installed a copy on the customers hardware and maybe kept a branch. Nothing was touched unless there was a bug or a re-configuration of the hardware or the flow so the system is left to age, security flaws and all.Connectivity combined with increased capability leads directly to increased exposure. The old approach means you are the weakest point in the eco-system and you cant get cyber insurance.

## What does this mean?

 The days of set it and forget it are done. Hackers and insurance companies have put Automation in the spotlight, so everyone has new expectations. There is a strong overlap with the rigor of standard software engineering and standard security principals.

## Know whats in your solution

 You need to know what is in your system, including those black boxes you buy. What is the hardware, firmware, software because that relates directly to vulnerability and maintenance. Unix, Windows, Android, iOS, RTOS - all platforms have weaknesses, so we need to know which version to understand the attack surface area and maintenance requirements.

## Prepare for update cycles

 Include budget or pricing for routine updates of the environment. Companies typically apply patches to operating systems once a month. You need personnel to make sure the patches dont break the automation after every update cycle.

## Update your components bi-annually

 Prepare to deploy a bi-annual update of your system and at the very least the operating systems.
 Worst case this is once a year.
 Include budget for the various licenses required and prepare test environments if possible.

## Scan your appliances Regularly

 scan your appliances for vulnerabilities and prepare to fix them within 90 days.
 You want to find and fix them before others exploit them. For vendors, having a security report with each unit is a selling feature.Minimize connectivityEnsure you have least privilege connectivity for your devices. The less connected the device the less risk you bring. Ensure you use updated VPN software for remote support and change the support passwords regularly or generate them uniquely.

## Over-the-air updates (OTA)

 Use tools like Azure IOT Hub to remotely update the devices securely.

 The technology is available to update all kinds of devices, chipsets and operating systems. It is worth the extra cost.

## Talk to your vendors / customers about security

 Make sure you are on the same page on security. Keeping the fortress sealed requires both parties working together.

## Why do you care?

 I dont want to be responsible for the hole in the wall that let the hackers in to the company network. Additionally, when automation breaks, the impact is typically tens of thousands of dollars per hour or more. Once exploited, securing the hole can take down your entire automation system for days. Lastly, those ransoms are a pretty expensive proposition. Talk about adding salt to a wound.

[My original LI article](https://www.linkedin.com/posts/briansrogers_promat2023-trg-activity-7043944571071864832-Qoxf?utm_source=share&utm_medium=member_desktop)
