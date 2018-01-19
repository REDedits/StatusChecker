# Status Checker

![screenshot_statuscheck](https://cloud.githubusercontent.com/assets/7362161/12534365/b9e8ccc8-c20a-11e5-968b-c82a317e7f6c.png)

### https://github.com/REDedits/StatusChecker.git


Developed for the purpose of creating a email request list for reference numbers.

First you create your contact list, which is then saved in the local storage of your browser (*please turn off delete history or you will lose this list upon exiting your browser*).

In the main request text area you can input a **six digit number** followed by the **contact name** you want to assign that number(s). 

Once you click the **Submit For Request button** those numbers will be added to the stored array for each contact. A hyperlink is created in the html below.

The hyperlink name should match the contact name you saved **exactly** case-sensitive. Clicking the link will open your local mail software (*IE outlook*).

The composed e-mail will include the email address or addresses if you used a semicolin to seperate multiple addresses when you saved the contact. The default Status Request text in the Subject line followed by the current date, generated by the Javascript Date UTC.

In the body of the email you will find a quick status request message followed by each reference number assigned to the contact.

Once you recieve an answer to your request you can save it and store it in local storage which will be referenced before the next request is generated. Currently the request will only include two special key words for status into the newly composed request ("delivered" and "Empty"). If a reference number is paired with either of these keywords it will add a message in the body of the email, next to the reference number to let the recepient know these items have that status and need to do something to change it.

#### Saving Status is currently a limited use case feature. It was developed for use in a Logistics office to help track loads that have been marked delivered or empty. The plan is to expand this section in the future to make it more customizable.

**Refresh Button** *will clear all the fields and reload the page, as will adding a new contact or clicking the cancel button.*

![screenshot_action_result](https://cloud.githubusercontent.com/assets/7362161/12534310/a6b1b8c0-c207-11e5-9055-11e561aaad3b.png)
