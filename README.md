# Verys React.js App

Help! Our app was working fine the other day, but something has happened and now it doesn't work right. We have an app that keeps track of items and helps the user choose one of those options. Here's how it should work:

- The user enters an item into the input box and clicks "Add Option" to add the item to the list.
- The user adds a few more items to the list.
- To choose an item at random the user clicks "What should I do?" to choose an item at random.

While the app is _mostly_ working there are a few issues that we've noticed:

- The buttons no longer look correct (see screenshot-working.png).
- The remove buttons don't work.
- Options should stay on the screen if you refresh the page. Currently, all options disappear if the user hits refresh.

How to run the app (note: you will need Node and Yarn installed):
1. Unzip the files.
2. In the command terminal, navigate to the root of the unzipped site.
3. Run `yarn install`.
4. Run `yarn run dev-server`.
5. In your browser, go to `http://localhost:8081` to see the site.