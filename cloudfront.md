origin <=> cloudfront
cloudfront <=> viewer
間の通信についてそれぞれhttpsの使用の有無を設定できる
cloudfront <=> viewer間の通信を設定する場合viewerProtocolPolicyを設定する

カスタムオリジン
    s3以外のオリジンのこと


カスタムURL
    CloudFrontにはデフォルトでドメインが設定されている
    aaaa1111.cloudfront.netみたいなやつ。
    このドメインを自分が持っているドメインに切り替えることができる。

