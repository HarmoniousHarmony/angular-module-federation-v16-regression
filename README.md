How to reproduce the bug:

Checkout `v-15` branch, run `npm i` and in two terminals run `ng s shell` and `ng s mfe1`.
You should be able to see both the sell app and the `mfe`.

Now switch to `v-16`, remove the `node_modules` folder and do another `npm i`, do the same steps above, you will see the app fails to load.
