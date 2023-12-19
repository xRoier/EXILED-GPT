# EXILED-GPT
This is the official repository for EXILED-GPT, it doesn't contain training data neither models, it's just used for creating Issues in wrong responses.

## How to contribute
If you want to submit your plugins to be converted to datasets and be part of the training data of EXILED-GPT just pull request your plugin folder into ``plugins``.
Keep in mind that the structure should look like this:
```
/plugins
   /Author-MyBeautifulPlugin
      /MyBeautifulPlugin.sln
      /what_it_does.txt
```
``what_it_does.txt``:
```
RESPONSE, EXAMPLE: My plugin adds SCP1162, a hole in SCP-173 old room walls that you can use to change your items to others. It mainly uses Exiled.Events.Handlers.X.Y event(s).
```
