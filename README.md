# fred

[![Join the chat at https://gitter.im/BugHunter2k/fred](https://badges.gitter.im/BugHunter2k/fred.svg)](https://gitter.im/BugHunter2k/fred?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
Frontend editing for Grav using contenttools or prosemirror

## Demo / Developement enviroment

1. Goto: http://new.judo-rietberg.de
* Use Login link and login with "testuser" and "Test12345" 
* Goto any blog-page and klcik on the blue pencil-icon in the upper left corner.
* Edit Content, finish with green checkmark button and the changes are written to .md-file


## TODOs
- decide which editor is the best
- invesitgate
 - make sure only markdown content is edited? Or what about twig content?
 - how to edit multi-language pages
 - how to edit modular pages
 - how to add site.editor access to users
 - how to best login users on frontend

### Other Things
- Possible related: https://github.com/getgrav/grav-plugin-admin/issues/346
 
 
## Done
- Using onPageProcessed Event to wrap rendered content with editable div
- use login-Plugin and access:site.editor for user authentification
- warp javascript in a closure function and autoload on jQuery-pageready 
- save changes to .md file


### Used Libs:
- https://github.com/domchristie/to-markdown
- http://getcontenttools.com/
