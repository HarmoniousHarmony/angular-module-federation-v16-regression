How to reproduce the bug:

Checkout `v-15` branch, run `npm i` and in two terminals run `ng s shell` and `ng s mfe1`.
You should be able to see both the sell app and the `mfe`.

Now switch to `v-16`, remove the `node_modules` folder and do another `npm i`, do the same steps above, and navidate to `flights` link by clicking on top menu link, you will see the app fails to load.

<img width="1206" alt="image" src="https://github.com/HarmoniousHarmony/angular-module-federation-v16-regression/assets/10879511/4f1418ca-de4c-4ddc-87e2-92cb093cc869">

