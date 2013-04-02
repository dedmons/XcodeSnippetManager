This script is used to manage Xcode code snippets. 
Inspired by https://github.com/lukeredpath/xcodesnippets but
I wanted to create a pure bash alternitave for fun.

It allows you to: 
  - Migrate: 
      Copy user snippets to shared folder with human readable names
  - Import:
      Import .codesnippet file to the managed folder and link into 
      Xcodes folder as well
  - Exprot:
      Exports all your user snippets in Xcodes folder to ~/XCSnippets
      or a folder you specify. Names files with human readble title.
  - Link:
      Links all the .codesnippet files in managed folder to Xcode folder.
      Usefull if you copy new snippet in without using import tool.
  - List:
      Lists all the snippets in the managed folder and Xcode folder by
      title and path.