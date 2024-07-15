# aria-live
aria-live is use to inform user any update on the page without sending focus to the particular element.
* aria-live="assertive": use to inform agent information interupting with screen reader current task
* aria-live="polite": use to inform user less inportant information than aira-live="assertive" until screen reader finish reading current task update information remain in que.
* role="alert": is use to provide immediate update any information on page. role="alert" is almost similar with aria-live="assertive" with a difference that role="alert" inform only change node not the adjacent information but role="assertive" with aria-atomic="true" inform change node including ajacent information.
* role="log": use to identify sequential information updates. The aria live region role of log has an implicit aria-live value of polite and aria-atomic value of false, which allows a user to be notified via AT (such as a screen reader) when log messages are added. Use Case - update chat conversaton, server log
* role="status": Use to notify less important information has an implicit role aria-live="polite"
* role="marquee": use to notify user when get focus has an implicit role aria-live="off"
* role="timer" use notify user after a certain period of time has an implicit role aria-live="off"
* aria-relevant="removals/additions/text": only the important information notify the screen reader.
* aria-bussy="true": Inforamtion is not ready yet to announce.
