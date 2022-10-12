### Github Actions - Xcode Test Report
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
   <img src="assets/2.png?raw=true#gh-light-mode-only">
   <img src="assets/2-dark.png?raw=true#gh-dark-mode-only">
</div>
