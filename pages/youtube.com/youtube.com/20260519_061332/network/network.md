# Network Log

این فایل خلاصه‌ی درخواست‌ها و پاسخ‌های ثبت‌شده توسط مرورگر است. جزئیات کامل در `network.json` و `network.jsonl` ذخیره شده است.

| # | Method | Type | Status | URL | Body |
|---:|---|---|---:|---|---|
| 1 | `GET` | `document` | 301 | `https://youtube.com/` | body unavailable: Response.body: Response body is unavailable for redirect responses |
| 2 | `GET` | `document` | 200 | `https://www.youtube.com/` | network/bodies/0002_document.html |
| 3 | `GET` | `other` | 204 | `https://i.ytimg.com/generate_204` | binary body skipped |
| 4 | `GET` | `script` | 200 | `https://www.youtube.com/s/_/ytmainappweb/_/js/k=ytmainappweb.kevlar_base.en_US.nmjlKbU1YAc.es5.O/am=AAAAAAgABAAJ/d=1/br=1/rs=AGKMywEOY-QJIJJ24IAIYx6kJzNzcIC9...` | network/bodies/0004_script.js |
| 5 | `GET` | `script` | 200 | `https://www.youtube.com/s/desktop/a79e727c/jsbin/web-animations-next-lite.min.vflset/web-animations-next-lite.min.js` | network/bodies/0005_script.js |
| 6 | `GET` | `script` | 200 | `https://www.youtube.com/s/desktop/a79e727c/jsbin/custom-elements-es5-adapter.vflset/custom-elements-es5-adapter.js` | network/bodies/0006_script.js |
| 7 | `GET` | `script` | 200 | `https://www.youtube.com/s/desktop/a79e727c/jsbin/webcomponents-sd.vflset/webcomponents-sd.js` | network/bodies/0007_script.js |
| 8 | `GET` | `script` | 200 | `https://www.youtube.com/s/desktop/a79e727c/jsbin/intersection-observer.min.vflset/intersection-observer.min.js` | network/bodies/0008_script.js |
| 9 | `GET` | `script` | 200 | `https://www.youtube.com/s/desktop/a79e727c/jsbin/scheduler.vflset/scheduler.js` | network/bodies/0009_script.js |
| 10 | `GET` | `script` | 200 | `https://www.youtube.com/s/desktop/a79e727c/jsbin/www-i18n-constants-en_US.vflset/www-i18n-constants.js` | network/bodies/0010_script.js |
| 11 | `GET` | `script` | 200 | `https://www.youtube.com/s/desktop/a79e727c/jsbin/spf.vflset/spf.js` | network/bodies/0011_script.js |
| 12 | `GET` | `script` | 200 | `https://www.youtube.com/s/desktop/a79e727c/jsbin/network.vflset/network.js` | network/bodies/0012_script.js |
| 13 | `GET` | `stylesheet` | 200 | `https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700&family=YouTube+Sans:wght@300..900&display=swap` | network/bodies/0013_stylesheet.css |
| 14 | `GET` | `stylesheet` | 200 | `https://www.youtube.com/s/desktop/a79e727c/cssbin/www-main-desktop-home-page-skeleton.css` | network/bodies/0014_stylesheet.css |
| 15 | `GET` | `stylesheet` | 200 | `https://www.youtube.com/s/desktop/a79e727c/cssbin/www-onepick.css` | network/bodies/0015_stylesheet.css |
| 16 | `GET` | `stylesheet` | 200 | `https://www.youtube.com/s/_/ytmainappweb/_/ss/k=ytmainappweb.kevlar_base.vZRuVKPMo24.L.B1.O/am=AAAAAAggBIAJ/d=0/br=1/rs=AGKMywHGnY5TmZvvDthyzW7TfY718tOlEQ` | network/bodies/0016_stylesheet.css |
| 17 | `GET` | `document` | 302 | `https://accounts.google.com/ServiceLogin?service=youtube&uilel=3&passive=true&continue=https%3A%2F%2Fwww.youtube.com%2Fsignin%3Faction_handle_signin%3Dtrue%2...` | body unavailable: Response.body: Response body is unavailable for redirect responses |
| 18 | `GET` | `stylesheet` | 200 | `https://www.youtube.com/s/desktop/a79e727c/cssbin/www-main-desktop-watch-page-skeleton.css` | network/bodies/0018_stylesheet.css |
| 19 | `GET` | `font` | 200 | `https://fonts.gstatic.com/s/roboto/v51/KFO7CnqEu92Fr1ME7kSn66aGLdTylUAMa3yUBA.woff2` | binary body skipped |
| 20 | `GET` | `document` | 302 | `https://accounts.google.com/InteractiveLogin?continue=https://www.youtube.com/signin?action_handle_signin%3Dtrue%26app%3Ddesktop%26hl%3Den%26next%3D%252Fsign...` | body unavailable: Response.body: Response body is unavailable for redirect responses |
| 21 | `GET` | `document` | 403 | `https://accounts.google.com/v3/signin/identifier?continue=https%3A%2F%2Fwww.youtube.com%2Fsignin%3Faction_handle_signin%3Dtrue%26app%3Ddesktop%26hl%3Den%26ne...` | network/bodies/0021_document.html |
| 22 | `GET` | `image` | 200 | `https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_150x54dp.png` | binary body skipped |
| 23 | `GET` | `xhr` | 302 | `https://googleads.g.doubleclick.net/pagead/id` | body unavailable: Response.body: Response body is unavailable for redirect responses |
| 24 | `GET` | `media` | 206 | `https://www.youtube.com/s/search/audio/failure.mp3` | binary body skipped |
| 25 | `GET` | `media` | 206 | `https://www.youtube.com/s/search/audio/no_input.mp3` | binary body skipped |
| 26 | `GET` | `media` | 206 | `https://www.youtube.com/s/search/audio/open.mp3` | binary body skipped |
| 27 | `GET` | `media` | 206 | `https://www.youtube.com/s/search/audio/success.mp3` | binary body skipped |
| 28 | `GET` | `xhr` | 200 | `https://googleads.g.doubleclick.net/pagead/id?slf_rd=1` | network/bodies/0028_xhr.json |
| 29 | `GET` | `script` | 200 | `https://www.google.com/js/th/fkgRGxP2obiIZAJBbVajXBEe7lZi3X0sYBGzgFACSFE.js` | network/bodies/0029_script.js |
| 30 | `GET` | `fetch` | 403 | `https://rr5---sn-ntqe6n7r.googlevideo.com/videoplayback?expire=1190963143&ei=L-1qi8SpOciMkAb3NfpP4Ze&ip=95.16.53.47&id=o-AF5lZw35B7iwmk742ESI5g9UtAArrKqEQ76o...` | body unavailable: Response.body: Protocol error (Network.getResponseBody): No data found for resource with given identifier |
| 31 | `GET` | `fetch` | 403 | `https://rr5---sn-ntqe6n7r.googlevideo.com/videoplayback?expire=1190963143&ei=L-1qi8SpOciMkAb3NfpP4Ze&ip=95.16.53.47&id=o-AF5lZw35B7iwmk742ESI5g9UtAArrKqEQ76o...` | body unavailable: Response.body: Protocol error (Network.getResponseBody): No data found for resource with given identifier |
| 32 | `POST` | `fetch` | 200 | `https://www.youtube.com/youtubei/v1/guide?prettyPrint=false` | network/bodies/0032_fetch.json |
| 33 | `GET` | `image` | 200 | `https://www.google.com/pagead/lvz?evtid=ACd6KtxocDCsEhCZTVkktQiA5iFdLajiSos_cSAwm2IY1ITihBU_fCBqI0RNISjJwFP5lIjebqESYK7rII5GC8yq_wiVgApoZQ&req_ts=1779171219&...` | binary body skipped |
| 34 | `GET` | `font` | 200 | `https://fonts.gstatic.com/s/youtubesans/v32/Qw38ZQNGEDjaO2m6tqIqX5E-AVS5_rSejo46_PCTRspJ0OosolrBEJL3HO_T7fE.woff2` | binary body skipped |
| 35 | `GET` | `stylesheet` | 200 | `https://fonts.googleapis.com/css?family=Roboto:300italic,400italic,500italic,700italic` | network/bodies/0035_stylesheet.css |
| 36 | `GET` | `stylesheet` | 200 | `https://fonts.googleapis.com/css?family=Roboto+Mono:400` | network/bodies/0036_stylesheet.css |
| 37 | `POST` | `fetch` | 200 | `https://www.youtube.com/youtubei/v1/feedback?prettyPrint=false` | network/bodies/0037_fetch.json |
| 38 | `GET` | `script` | 200 | `https://www.youtube.com/s/player/55b1ff8b/player_es6.vflset/en_US/base.js` | network/bodies/0038_script.js |
| 39 | `GET` | `stylesheet` | 200 | `https://www.youtube.com/s/player/55b1ff8b/www-player.css` | network/bodies/0039_stylesheet.css |
| 40 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/search/v15/24px.svg` | network/bodies/0040_fetch.svg |
| 41 | `GET` | `image` | 204 | `https://www.youtube.com/generate_204?ezm0fw` | binary body skipped |
| 42 | `GET` | `fetch` | 301 | `https://youtube.com/` | body unavailable: Response.body: Response body is unavailable for redirect responses |
| 43 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/menu/v1/24px.svg` | network/bodies/0043_fetch.svg |
| 44 | `GET` | `fetch` | 200 | `https://www.gstatic.com/youtube/img/icons/web/youtube_fill/yt-logo-updated/v3/24px.svg` | network/bodies/0044_fetch.svg |
| 45 | `POST` | `xhr` | 200 | `https://www.youtube.com/api/jnn/v1/GenerateIT` | network/bodies/0045_xhr.txt |
| 46 | `GET` | `fetch` | 403 | `https://rr5---sn-ntqe6n7r.googlevideo.com/videoplayback?expire=1190963143&ei=L-1qi8SpOciMkAb3NfpP4Ze&ip=95.16.53.47&id=o-AF5lZw35B7iwmk742ESI5g9UtAArrKqEQ76o...` | body unavailable: Response.body: Protocol error (Network.getResponseBody): No data found for resource with given identifier |
| 47 | `GET` | `fetch` | 403 | `https://rr5---sn-ntqe6n7r.googlevideo.com/videoplayback?expire=1190963143&ei=L-1qi8SpOciMkAb3NfpP4Ze&ip=95.16.53.47&id=o-AF5lZw35B7iwmk742ESI5g9UtAArrKqEQ76o...` | body unavailable: Response.body: Protocol error (Network.getResponseBody): No data found for resource with given identifier |
| 48 | `GET` | `fetch` |  | `https://www.youtube.com/` |  |
| 49 | `GET` | `fetch` | 200 | `https://www.gstatic.com/youtube/img/icons/web/youtube_outline/refresh/v1/24px.svg` | network/bodies/0049_fetch.svg |
| 50 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/chevron_down/v9/24px.svg` | network/bodies/0050_fetch.svg |
| 51 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/mic/v14/24px.svg` | network/bodies/0051_fetch.svg |
| 52 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/person_circle/v10/24px.svg` | network/bodies/0052_fetch.svg |
| 53 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/overflow_vertical/v13/24px.svg` | network/bodies/0053_fetch.svg |
| 54 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_fill_experimental/home/v10/24px.svg` | network/bodies/0054_fetch.svg |
| 55 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/shorts/v3/24px.svg` | network/bodies/0055_fetch.svg |
| 56 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/subscriptions/v12/24px.svg` | network/bodies/0056_fetch.svg |
| 57 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/history/v1/24px.svg` | network/bodies/0057_fetch.svg |
| 58 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/bag/v7/24px.svg` | network/bodies/0058_fetch.svg |
| 59 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/audio/v14/24px.svg` | network/bodies/0059_fetch.svg |
| 60 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/clapperboard/v3/24px.svg` | network/bodies/0060_fetch.svg |
| 61 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/chevron_up/v9/24px.svg` | network/bodies/0061_fetch.svg |
| 62 | `GET` | `fetch` | 200 | `https://www.gstatic.com/youtube/img/icons/web/youtube_fill/youtube_round/v2/24px.svg` | network/bodies/0062_fetch.svg |
| 63 | `GET` | `fetch` | 200 | `https://www.gstatic.com/youtube/img/icons/web/youtube_fill/unplugged_logo/v2/24px.svg` | network/bodies/0063_fetch.svg |
| 64 | `GET` | `fetch` | 200 | `https://www.gstatic.com/youtube/img/icons/web/youtube_fill/youtube_music/v2/24px.svg` | network/bodies/0064_fetch.svg |
| 65 | `GET` | `fetch` | 200 | `https://www.gstatic.com/youtube/img/icons/web/youtube_fill/youtube_kids_round/v2/24px.svg` | network/bodies/0065_fetch.svg |
| 66 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/flag/v10/24px.svg` | network/bodies/0066_fetch.svg |
| 67 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/x/v11/24px.svg` | network/bodies/0067_fetch.svg |
| 68 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/location_pin/v2/24px.svg` | network/bodies/0068_fetch.svg |
| 69 | `GET` | `script` | 200 | `https://www.youtube.com/s/_/ytmainappweb/_/js/k=ytmainappweb.kevlar_base.en_US.nmjlKbU1YAc.es5.O/am=AAAAAAgABAAJ/d=1/exm=kevlar_base_module,kevlar_base_sync_...` | network/bodies/0069_script.js |
| 70 | `GET` | `script` | 200 | `https://www.youtube.com/s/_/ytmainappweb/_/js/k=ytmainappweb.kevlar_base.en_US.nmjlKbU1YAc.es5.O/am=AAAAAAgABAAJ/d=1/exm=De8mUc,QlbBce,kevlar_base_module,kev...` | network/bodies/0070_script.js |
| 71 | `GET` | `script` | 200 | `https://www.youtube.com/s/player/55b1ff8b/player_es6.vflset/en_US/offline.js` | network/bodies/0071_script.js |
| 72 | `GET` | `script` | 200 | `https://www.youtube.com/s/player/55b1ff8b/player_es6.vflset/en_US/remote.js` | network/bodies/0072_script.js |
| 73 | `GET` | `script` | 200 | `https://www.youtube.com/s/player/55b1ff8b/player_es6.vflset/en_US/miniplayer.js` | network/bodies/0073_script.js |
| 74 | `GET` | `script` | 200 | `https://www.gstatic.com/cv/js/sender/v1/cast_sender.js` | network/bodies/0074_script.js |
| 75 | `GET` | `script` | 200 | `https://static.doubleclick.net/instream/ad_status.js` | network/bodies/0075_script.js |
| 76 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_fill_experimental/add_circle/v6/24px.svg` | network/bodies/0076_fetch.svg |
| 77 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/add_circle/v6/24px.svg` | network/bodies/0077_fetch.svg |
| 78 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/alert_bubble/v2/24px.svg` | network/bodies/0078_fetch.svg |
| 79 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_fill_experimental/audio/v14/24px.svg` | network/bodies/0079_fetch.svg |
| 80 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_fill_experimental/bag/v7/24px.svg` | network/bodies/0080_fetch.svg |
| 81 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_fill_experimental/bell/v11/24px.svg` | network/bodies/0081_fetch.svg |
| 82 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/bell/v11/24px.svg` | network/bodies/0082_fetch.svg |
| 83 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_fill_experimental/clapperboard/v3/24px.svg` | network/bodies/0083_fetch.svg |
| 84 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_fill_experimental/clock/v10/24px.svg` | network/bodies/0084_fetch.svg |
| 85 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/clock/v10/24px.svg` | network/bodies/0085_fetch.svg |
| 86 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/copy/v3/24px.svg` | network/bodies/0086_fetch.svg |
| 87 | `GET` | `fetch` | 200 | `https://www.gstatic.com/youtube/img/icons/web/youtube_fill/creator_studio_red_logo/v2/24px.svg` | network/bodies/0087_fetch.svg |
| 88 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/download/v11/24px.svg` | network/bodies/0088_fetch.svg |
| 89 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_fill_experimental/fashion/v4/24px.svg` | network/bodies/0089_fetch.svg |
| 90 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/fashion/v4/24px.svg` | network/bodies/0090_fetch.svg |
| 91 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_fill_experimental/flag/v10/24px.svg` | network/bodies/0091_fetch.svg |
| 92 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_fill_experimental/gaming/v3/24px.svg` | network/bodies/0092_fetch.svg |
| 93 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/gaming/v3/24px.svg` | network/bodies/0093_fetch.svg |
| 94 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_fill_experimental/gear/v10/24px.svg` | network/bodies/0094_fetch.svg |
| 95 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/gear/v10/24px.svg` | network/bodies/0095_fetch.svg |
| 96 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/help_circle/v2/24px.svg` | network/bodies/0096_fetch.svg |
| 97 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/home/v10/24px.svg` | network/bodies/0097_fetch.svg |
| 98 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_fill_experimental/lightbulb/v4/24px.svg` | network/bodies/0098_fetch.svg |
| 99 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/lightbulb/v4/24px.svg` | network/bodies/0099_fetch.svg |
| 100 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/live/v3/24px.svg` | network/bodies/0100_fetch.svg |
| 101 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_fill_experimental/mic/v14/24px.svg` | network/bodies/0101_fetch.svg |
| 102 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_fill_experimental/news/v3/24px.svg` | network/bodies/0102_fetch.svg |
| 103 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/news/v3/24px.svg` | network/bodies/0103_fetch.svg |
| 104 | `GET` | `fetch` | 200 | `https://www.gstatic.com/youtube/img/icons/web/youtube_fill/offline_no_content/v1/192px.svg` | network/bodies/0104_fetch.svg |
| 105 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/overflow_horizontal/v6/24px.svg` | network/bodies/0105_fetch.svg |
| 106 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_fill_experimental/play_square_stack/v1/24px.svg` | network/bodies/0106_fetch.svg |
| 107 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/play_square_stack/v1/24px.svg` | network/bodies/0107_fetch.svg |
| 108 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/playlist/v5/24px.svg` | network/bodies/0108_fetch.svg |
| 109 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_fill_experimental/podcast/v6/24px.svg` | network/bodies/0109_fetch.svg |
| 110 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/podcast/v6/24px.svg` | network/bodies/0110_fetch.svg |
| 111 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_fill_experimental/search/v15/24px.svg` | network/bodies/0111_fetch.svg |
| 112 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_fill_experimental/subscriptions/v12/24px.svg` | network/bodies/0112_fetch.svg |
| 113 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_fill_experimental/thumb_up/v23/24px.svg` | network/bodies/0113_fetch.svg |
| 114 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/thumb_up/v23/24px.svg` | network/bodies/0114_fetch.svg |
| 115 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_fill_experimental/trash_can/v10/24px.svg` | network/bodies/0115_fetch.svg |
| 116 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/trash_can/v10/24px.svg` | network/bodies/0116_fetch.svg |
| 117 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_fill_experimental/trending/v2/24px.svg` | network/bodies/0117_fetch.svg |
| 118 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/trending/v2/24px.svg` | network/bodies/0118_fetch.svg |
| 119 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_fill_experimental/trophy/v3/24px.svg` | network/bodies/0119_fetch.svg |
| 120 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/trophy/v3/24px.svg` | network/bodies/0120_fetch.svg |
| 121 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_fill_experimental/video/v3/24px.svg` | network/bodies/0121_fetch.svg |
| 122 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/video/v3/24px.svg` | network/bodies/0122_fetch.svg |
| 123 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/video_camera_add/v2/24px.svg` | network/bodies/0123_fetch.svg |
| 124 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_fill_experimental/youtube_shorts/v11/24px.svg` | network/bodies/0124_fetch.svg |
| 125 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/youtube_shorts/v11/24px.svg` | network/bodies/0125_fetch.svg |
| 126 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/arrow_down/v3/24px.svg` | network/bodies/0126_fetch.svg |
| 127 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/arrow_up/v3/24px.svg` | network/bodies/0127_fetch.svg |
| 128 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_fill_experimental/pause/v9/24px.svg` | network/bodies/0128_fetch.svg |
| 129 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_fill_experimental/play/v4/24px.svg` | network/bodies/0129_fetch.svg |
| 130 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/play/v4/24px.svg` | network/bodies/0130_fetch.svg |
| 131 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_fill_experimental/share/v12/24px.svg` | network/bodies/0131_fetch.svg |
| 132 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/share/v12/24px.svg` | network/bodies/0132_fetch.svg |
| 133 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_fill_experimental/text_bubble/v4/24px.svg` | network/bodies/0133_fetch.svg |
| 134 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/text_bubble/v4/24px.svg` | network/bodies/0134_fetch.svg |
| 135 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_fill_experimental/thumb_down/v25/24px.svg` | network/bodies/0135_fetch.svg |
| 136 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/thumb_down/v25/24px.svg` | network/bodies/0136_fetch.svg |
| 137 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_fill_experimental/volume_max/v2/24px.svg` | network/bodies/0137_fetch.svg |
| 138 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/volume_max/v2/24px.svg` | network/bodies/0138_fetch.svg |
| 139 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_fill_experimental/volume_mute/v2/24px.svg` | network/bodies/0139_fetch.svg |
| 140 | `GET` | `fetch` | 200 | `https://fonts.gstatic.com/s/i/youtube_outline_experimental/volume_mute/v2/24px.svg` | network/bodies/0140_fetch.svg |
| 141 | `GET` | `fetch` | 200 | `https://www.gstatic.com/youtube/img/icons/web/youtube_outline/waveform/v1/24px.svg` | network/bodies/0141_fetch.svg |
| 142 | `GET` | `fetch` | 403 | `https://rr5---sn-ntqe6n7r.googlevideo.com/videoplayback?expire=1190963143&ei=L-1qi8SpOciMkAb3NfpP4Ze&ip=95.16.53.47&id=o-AF5lZw35B7iwmk742ESI5g9UtAArrKqEQ76o...` | body unavailable: Response.body: Protocol error (Network.getResponseBody): No data found for resource with given identifier |
| 143 | `GET` | `fetch` | 403 | `https://rr5---sn-ntqe6n7r.googlevideo.com/videoplayback?expire=1190963143&ei=L-1qi8SpOciMkAb3NfpP4Ze&ip=95.16.53.47&id=o-AF5lZw35B7iwmk742ESI5g9UtAArrKqEQ76o...` | body unavailable: Response.body: Protocol error (Network.getResponseBody): No data found for resource with given identifier |
| 144 | `POST` | `xhr` | 200 | `https://www.youtube.com/youtubei/v1/log_event?alt=json` | network/bodies/0144_xhr.json |
