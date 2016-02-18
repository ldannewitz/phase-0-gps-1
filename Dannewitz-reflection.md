GPS 1.1 - Version Control and Git
-Dannewitz Reflection

1. What git concepts were you struggling with prior to the GPS session?
  * I had never used the commands fetch and merge so we struggled a bit with those in the GPS session.

2. What concepts were clarified during the GPS?
  * The GPS really just solidified everything we've learned thus far about git. Using the markdown like bold and italics was great practice. After working with html this week, we had to reorient a bit back to the git markdown.

3. What questions did you ask your pair and the guide?
  * Because of the fetch and merge confusion, we asked the guide for clarification on how those commands differ from pull.
  * I also asked the guide about SSH keys on GitHub and an irregularity I'm having in my bash profile. The branch names show up as [\[\e[0;32m\]master\[\e[0m\]]:>, which you can imagine gets rather annoying to look at after awhile.

4. What still confuses you about git?
  * The process of going through a merge conflict still confuses me. We followed the steps, and everything seemed to work how it should according to the directions.
  * Here's what confuses me. After you get this notation:
  >[<<<<<<<<<<<HEAD<<<<<<<<<<<<<<<<<<]
  >[some_code]
  >[==================================]
  >[other_code]
  >[>>>>>>>>>>>>small_conflict>>>>>>]

  * ...and you choose one code to keep and delete everything else, what is the next step? Are you supposed to merge the local feature-branch with the local master-branch? Or do you have to push to origin?
  * We tried merging the two local branches after resolving the conflict, but we couldn't get them to merge.

5. How was your first experience of pairing in a GPS?
  * I thought it was great! Having the guide there was helpful, and I thought the entire session was extremely productive.