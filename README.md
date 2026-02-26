# [iOS UniversalLink](https://medium.com/zrealm-ios-dev/universal-links-新鮮事-12c5026da33d)
> apple-app-site-association（AASA）檔案是用來支援 iOS Universal Links，讓網站連結能直接開啟 App。

- [先確定檔案讀不讀得到](https://blog.dreambreakerx.com/2018/09/universal-links/)
> ```html
> https://app-iit-hk.github.io/.well-known/apple-app-site-association
> ```

- [也可以用指令測試](https://tom8u4286.medium.com/ios-universal-link實作-51b7ec277f3a)
> ```bash
> sudo swcutil dl -d app-iit-hk.github.io --verbose
> ```

- [檢查Apple's CDN](https://support.apple.com/zh-tw/101555)
> ```bash
> curl https://app-site-association.cdn-apple.com/a/v1/app-iit-hk.github.io
> ```

- [也有套件可以測試](https://st-tech.github.io/universal-links-test/)
> ```html
> https://github.com/st-tech/universal-links-test
> ```

- [也可以參考Google的設定值](https://branch.io/resources/aasa-validator/)
> ```html
> https://www.google.com/apple-app-site-association
> ```
