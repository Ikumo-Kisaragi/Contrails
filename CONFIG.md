
# recordName

> This is the feed's ID which can be letters, numbers, or dashes. Spaces are not allowed. Maximum length is 15 characters.

My-List

# displayName

> This is the title of the custom feed. Maximum length is 24 characters.

「深層組」所属タレント

# description

> This is the description of the feed.

VTuber事務所「深層組」所属タレント のフィード<br>
ご本人へのリプライ「含む」<br>
ご本人のリポスト「含む」<br>
<br>
◾️現在のタレントリスト<br>
　・従井ノラ<br>
　・わからせちょろ<br>
　・刺杉あいす<br>
　・数打あたる<br>

# searchTerms

> There are three types of search terms:
>
> - Keywords: Test these in [https://bsky.app/search](https://bsky.app/search). `AND` is implicit, so `cat dog` on one line will require both `cat` and `dog`. You can use quotes as well `"hot dog"`.
> - Users: links such as `https://bsky.app/profile/why.bsky.team` will pull in the user's posts. To include replies and reposts, you can add the following flags: `https://bsky.app/profile/why.bsky.team +replies +reposts`.
> - Pinned posts: links such as `https://bsky.app/profile/saddymayo.bsky.social/post/3jxju2wwap22e` will pin at the top of the feed. One link per line, please.

> 従井ノラ
- https://bsky.app/profile/norashitagai.bsky.social +replies +reposts

> 刺杉あいす
- https://bsky.app/profile/sashisugiaisu.bsky.social +replies +reposts

> 数打あたる
- https://bsky.app/profile/atarukazuuchi.bsky.social +replies +reposts

> わからせちょろ
- https://bsky.app/profile/choronya.bsky.social +replies +reposts

# denyList

> Deny list will exclude any results from a given user. You can provide the username or DID.
>
> - did:plc:1234
> - @spamspamspam.bsky.social

# safeMode

> Safe mode limits the total number of API calls coming from Cloudflare.
>
> Set to `false` if you have higher limits via a paid Cloudflare plan.

false

# avatar

> This must link to an image (PNG or JPEG) in the same directory as this CONFIG.md. It doesn't have to be called `avatar.png`, but just be sure this CONFIG.md points to the correct file.

![](avatar.png)
