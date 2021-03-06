Contribution Guideline
======================

Thank you for the interest and potential effort.
Before you start to work on a pull request, please carefully read the following.

 * Look at the rest of the code and try to stick to the code style. Ugly code
   won't be merged.
 * If you plan to make a bigger change, you might want to open an issue first
   and discuss the idea and possible implementations with the developer team.
   Otherwise, it might turn out that your idea does not fit the gist of the
   project, your pull request gets rejected, and you feel like you've wasted
   your time. We don't want that!
 * Note that server-side code is mostly written in [CoffeeScript](https://coffeescript.org/).
   So don't change code in files like `xyz.js` if, in the same directory, there
   is a file like `xyz.coffee`. This means that the javascript file was
   generated by the CoffeeScript compiler. You can also see this by a comment at
   the beginning of the js file similar to `// Generated by CoffeeScript 1.10.0`.
   In this case you have to make the changes to the `.coffee` file(s) only and
   run the compiler to generate the `.js` file(s).
 * Usually you should file your pull request against the `develop` branch
   and most certainly not the `master` branch which is reserved for releases.
 * When you're done, don't forget to briefly describe the changes made in the
   [CHANGELOG](CHANGELOG.md#upcoming) under the section "Upcoming".

For setting up the development environment check out the section
[Developing in the README](README.md#developing).

If you're having problems, you might find help on the
[troubleshooting](TROUBLESHOOTING.md) page. If not feel free to open an issue or
contact one of the developers.

Thanks for reading. This will probably save you and us valuable time.