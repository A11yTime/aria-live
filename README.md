# aria-live
aria-live is use to inform user any update on the page without sending focus to the particular element.
* aria-live="assertive": use to inform agent information interupting with screen reader current task
* aria-live="polite": use to inform user less inportant information than aira-live="assertive" until screen reader finish reading current task update information remain in que.
* role="alert": is use to provide immediate update any information on page. role="alert" is almost similar with aria-live="assertive" with a difference that role="alert" inform only change node not the adjacent information but role="assertive" with aria-atomic inform change node including ajacent information.
* 
