# Usability Test Report

Prepared by Facilitator, Aleisha

Based on [Aleisha's notes](https://gitlab.ecs.vuw.ac.nz/swen303-2019-p3/t8/final-project/wikis/Testing/Results/Aleisha-notes), [Jaimar's notes](https://gitlab.ecs.vuw.ac.nz/swen303-2019-p3/t8/final-project/wikis/Testing/Results/Jaimar-notes), [Post test questionnaire](https://gitlab.ecs.vuw.ac.nz/swen303-2019-p3/t8/final-project/wikis/Testing/Results/Post-test-questionnaire) and [Pre test questionnaire](https://gitlab.ecs.vuw.ac.nz/swen303-2019-p3/t8/final-project/wikis/Testing/Results/Pre-test-questionnaire)

The Usability Tests provided us with some useful user feedback about our prototype. This report is a presentation of the received feedback and test results, evaluate the usability metrics against the pre-approved goals, subjective evaluations, and specific usability problems and recommendations for resolution. The recommendations will be categorically sized by development to aid in the implementation strategy.

## Metrics and goals

Completion success and error rates showed what functionality was missing or incomplete in our prototype. Time-to-completion of scenarios was useful because it showed which scenarios took longer to complete, often due to design/layout flaws. However, the best feedback was received through subjective evaluations and commentary while testing.

Our goals with this testing were to establish a baseline of user performance, establish and validate user performance measures, and identify potential design concerns to be addressed in order to improve the efficiency, productivity, and end-user satisfaction.

Metrics such as 'time-on-task' showed whether scenarios can be completed 'quickly and easily', as is one of our usability goals. Subjective evaluations and commentary gave us deeper insight into potential design concerns and how efficient and satisfying the interface is for our users.

# Results

## Timings (minutes)

| | Tester 1 | Tester 2 | Tester 3 | Tester 4 | Tester 5 | Tester 6 | Tester 7 | **Avg** |
| - | - | - | - | - | - | - | - | - |
| Opening | 1:00 | 0:47 | 0:55 | 0:41 | 0:35 | 0:28 | 0:23 | **0:41** |
| Messaging | 1:40 | 2:43 | 2:01 | 1:06 | 2:01 | 0:56 | 1:21 | **1:35** |
| Room bookings | 2:30 | 2:00 | 1:19 | 1:06 | 1:08 | 0:57 | 2:44 | **1:41** |
| Calendar | 1:00 | 2:05 | 1:01 | 0:50 | 2:10 | 1:20 | 1:00 | **1:21** |

#### OPENING

| Test task | Completion rate | Error-free rate | Notes |
| - | - | - | - |
| Log in | 100% | 100% | |
| Find project management resources | 100% | 100% | Heading is lengthy and dropdown isn't expected display |
| View notifications | 100% | 100% | Wasn't clear there were unread/new notifications |
| Log out | 100% | 100% | Power button seems unnatural |

#### MESSAGING

| Test task | Completion rate | Error-free rate | Notes |
| - | - | - | - |
| Log in | 100% | 100% | |
| Find a user to send a private message | 100% | 86% | 1 tester looked to top navigation for messaging system |
| Expand the message box | 100% | **43%** | This test task was unclear, some testers thought simply opening a chat with someone was expanding the message box, but our intention was enlarging the chat box to the full page interface |
| Share a file | 100% | 100% | |
| Download a shared file | 100% | 100% | The confirmation pop-up box is unnecessary - might want to download more files and pop-up means extra clicks |
| Find a group chat | 100% | 100% | |
| Report a message/user | 100% | **71%** | The report message function hadn't been linked, and the report user function is only accessible on full page interface |
| TUTORS/LECTURERS ONLY: View reported users and messages | **0%** | **0%** | Not yet linked, couldn't test |

#### ROOM BOOKINGS

| Test task | Completion rate | Error-free rate | Notes |
| - | - | - | - |
| View room bookings | 100% | 100% | |
| Edit room booking | 100% | 100% | There is no way to delete room booking and editing invitees is confusing |
| Join an existing room booking | 100% | 100% | Want to stay on this page after joining a booking, not get redirected to Home | 
| Create a room booking | 100% | 100% | | 

#### CALENDAR

| Test task | Completion rate | Error-free rate | Notes |
| - | - | - | - |
| View calendar | 100% | 100% | |
| Toggle different views of calendar (Day, Week, Month) | 100% | 86% | Expected the views options to be higher in sidebar or at top of page, hard to click on. 1 tester clicked the button instead of the button text and view didn't toggle as it should |
| View a calendar booking | **0%** | **0%** | Unable to view a full calendar booking, takes you straight to delete function | 
| Add a calendar booking | 100% | **43%** | Many clicked 'add calendar' button first. No way to confirm a new calendar event |
| Delete a calendar booking | 100% | 100% | This shouldn't be the first pop-up when clicking on an existing calendar event. No way to edit an event | 
| Return home | 100% | **0%** | Already on 'home' if on calendar |

## Problems

| Problem | Impact | Frequency | Severity |
| - | - | - | - |
| Wasn't clear there were unread/new notifications | Low | Low | 4 |
| There is a lot of space on the page for a web-app, maybe have chat open always by default | Low | Low | 4 |
| **Power sign as logout doesn’t make sense** | Low | High | 2 |
| Project management tools heading too long | Low | Low | 4 |
| Project management tools should be text not pictures | Low | Medium | 3 |
| **2 links are redundant for home and calendar if show same thing** | Low | High | 2 |
| **No way to ‘go back’ from the expanded chat page** | Medium | High | 2 |
| **No way to ‘shrink’ expanded chat page back to small popup** | Medium | Medium | 2
| **Downloading file closes chat box** | High | Medium | 1 |
| Should be able to click whole file to download it, not just little download icon | Low | Low | 4 |
| **Can only report user from full page message view** | Medium | High | 2 |
| Upload file icon is unfamiliar | Low | Low | 4 |
| Cancel bookings form not linked back to Room bookings home | Low | Medium | 3
| **Redirected to Home after making a booking or requesting to join an existing booking** | Medium | High | 2 |
| **No way to delete a room booking** | High | Medium | 1 |
| X button doesn’t work to close confirm box after requesting to join | Low | Medium | 3 |
| Unclear what room booking privacy means | Low | Medium | 3 |
| Removing students from a room booking when editing is confusing | Low | Low | 4 |
| Not obvious calendars can be scrolled | Low | Low | 4 |
| **Calendar views are too low/not easy to find/hard to click** | Medium | High | 2 |
| Hard to visually separate calendar days | Low | Low | 4 |
| **'add calendar' button clicked before 'add event' button** | Medium | High | 2 |
| **No way to view whole calendar event/edit calendar event** | High | High | 1 |
| **Can't confirm adding a calendar event** | Medium | Medium | 2 |
| The confirmation pop-up box is unnecessary | Low | Medium | 3 |

## Recommendations

We were able to gather lots of feedback and found many large and small problems in our prototype. I would recommend tackling all of the problems with severity levels 1 and 2 because these problems made operations either impossible or slow/difficult. The other problems can be fixed if there is time, but they are not urgent and do not prevent our prototype from reaching our usability goals.