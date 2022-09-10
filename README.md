# CyberTooth Software, 2022
FRC 3940 CyberTooth's software platform for the 2022 offseason.

Initial commit is a clone of the code used during the 2022 season. Future commits will modify and upgrade the existing platform.

I've broken my personal goals down into three categories and ordered them by priority.

TELEOPERATED SOFTWARE--------------------------------------------------------------------------------------------------------------------------------

  (1) Altered controller implementation to make programming new controls easier -> Completed
  
  (2) Speed controlled ball path implementation (indexer & accelerator)
  
  (3) Multi-speed ball path implementation (indexer & accelerator)
  
  (4) Autonomous target locking and firing with shooter table
  
  (5) Driver feedback via onboard LEDs
  
  (6) Drive system tuning


AUTONOMOUS SOFTWARE-------------------------------------------------------------------------------------------------------------------------------

  (1) Auto commands implementation. This may entail a refactoring of how teleop works as well, but this is my #1 priority. -> In Progress
  
  (2) Concurrency in auto routines. -> Pending Testing
  
  (3) Build play via text/text parser from file. -> Completed


OTHER SOFTWARE-----------------------------------------------------------------------------------------------------------------------------------------

  (1) Dashboard rewrite (basically make it significantly more useful)
  
  (2) Controller vibration for driver feedback
  
  (3) Error classificatioon and display to dashboard. I have a few ideas for groups of errors, but this is honestly the bottom of my list for now, since it's per robot implem.
