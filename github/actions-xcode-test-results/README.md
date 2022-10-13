### Github Actions - Xcode Test Results
Great [Github Action](https://github.com/kishikawakatsumi/xcresulttool) by [kishikawakatsumi](https://github.com/kishikawakatsumi)

```ruby
- name: Create Test Results
        uses: kishikawakatsumi/xcresulttool@v1
        if: success() || failure()
        with:
          path: <path-to-result>.xcresult
```

<div align="center">
   <img src="assets/1.png?raw=true#gh-light-mode-only">
   <img src="assets/1-dark.png?raw=true#gh-dark-mode-only">
   <br />
   <em>Summary with all passed/failed/skipped tests and the time it took to run them all.</em>
   <br />
   <img src="assets/2.png?raw=true#gh-light-mode-only">
   <img src="assets/2-dark.png?raw=true#gh-dark-mode-only">
   <br />
   <em>Overview of all tests per TestCase.</em>
   <br />
</div>
