[Build an AngularJS App From Scratch: Getting Started](https://egghead.io/series/angularjs-app-from-scratch-getting-started) on egghead.io

## Egghead.io Eggly App
- .complete files are the finished app.  
- my *Original* branch will start from 'Simple States' adding bookmarks

### Simple States branch:
- Add, Edit, Delete Bookmarks
1. add button to create bookmark
2. new a Form to add bookmark      (delete cancel stub)
3. CRUD the controller
- use angular.copy when editing an item
- use *_.findIndex* to get correct bookmark
- Highlight bookmark being edited -- ng-class="{'active':isSelectedBookmark(bookmark.id)}"
- sets bookmark to edit && starts editing:
- - ng-click="setEditedBookmark(bookmark);startEditing();"
