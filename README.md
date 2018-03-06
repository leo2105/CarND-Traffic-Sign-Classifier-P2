 Traffic\_Sign\_Classifier   /\*! \* \* Twitter Bootstrap * */ /*! * Bootstrap v3.3.7 (http://getbootstrap.com) * Copyright 2011-2016 Twitter, Inc. * Licensed under MIT (https://github.com/twbs/bootstrap/blob/master/LICENSE) */ /*! normalize.css v3.0.3 | MIT License | github.com/necolas/normalize.css */ html { font-family: sans-serif; -ms-text-size-adjust: 100%; -webkit-text-size-adjust: 100%; } body { margin: 0; } article, aside, details, figcaption, figure, footer, header, hgroup, main, menu, nav, section, summary { display: block; } audio, canvas, progress, video { display: inline-block; vertical-align: baseline; } audio:not(\[controls\]) { display: none; height: 0; } \[hidden\], template { display: none; } a { background-color: transparent; } a:active, a:hover { outline: 0; } abbr\[title\] { border-bottom: 1px dotted; } b, strong { font-weight: bold; } dfn { font-style: italic; } h1 { font-size: 2em; margin: 0.67em 0; } mark { background: #ff0; color: #000; } small { font-size: 80%; } sub, sup { font-size: 75%; line-height: 0; position: relative; vertical-align: baseline; } sup { top: -0.5em; } sub { bottom: -0.25em; } img { border: 0; } svg:not(:root) { overflow: hidden; } figure { margin: 1em 40px; } hr { box-sizing: content-box; height: 0; } pre { overflow: auto; } code, kbd, pre, samp { font-family: monospace, monospace; font-size: 1em; } button, input, optgroup, select, textarea { color: inherit; font: inherit; margin: 0; } button { overflow: visible; } button, select { text-transform: none; } button, html input\[type="button"\], input\[type="reset"\], input\[type="submit"\] { -webkit-appearance: button; cursor: pointer; } button\[disabled\], html input\[disabled\] { cursor: default; } button::-moz-focus-inner, input::-moz-focus-inner { border: 0; padding: 0; } input { line-height: normal; } input\[type="checkbox"\], input\[type="radio"\] { box-sizing: border-box; padding: 0; } input\[type="number"\]::-webkit-inner-spin-button, input\[type="number"\]::-webkit-outer-spin-button { height: auto; } input\[type="search"\] { -webkit-appearance: textfield; box-sizing: content-box; } input\[type="search"\]::-webkit-search-cancel-button, input\[type="search"\]::-webkit-search-decoration { -webkit-appearance: none; } fieldset { border: 1px solid #c0c0c0; margin: 0 2px; padding: 0.35em 0.625em 0.75em; } legend { border: 0; padding: 0; } textarea { overflow: auto; } optgroup { font-weight: bold; } table { border-collapse: collapse; border-spacing: 0; } td, th { padding: 0; } /*! Source: https://github.com/h5bp/html5-boilerplate/blob/master/src/css/main.css */ @media print { *, *:before, *:after { background: transparent !important; color: #000 !important; box-shadow: none !important; text-shadow: none !important; } a, a:visited { text-decoration: underline; } a\[href\]:after { content: " (" attr(href) ")"; } abbr\[title\]:after { content: " (" attr(title) ")"; } a\[href^="#"\]:after, a\[href^="javascript:"\]:after { content: ""; } pre, blockquote { border: 1px solid #999; page-break-inside: avoid; } thead { display: table-header-group; } tr, img { page-break-inside: avoid; } img { max-width: 100% !important; } p, h2, h3 { orphans: 3; widows: 3; } h2, h3 { page-break-after: avoid; } .navbar { display: none; } .btn > .caret, .dropup > .btn > .caret { border-top-color: #000 !important; } .label { border: 1px solid #000; } .table { border-collapse: collapse !important; } .table td, .table th { background-color: #fff !important; } .table-bordered th, .table-bordered td { border: 1px solid #ddd !important; } } @font-face { font-family: 'Glyphicons Halflings'; src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot'); src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot?#iefix') format('embedded-opentype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff2') format('woff2'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff') format('woff'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.ttf') format('truetype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.svg#glyphicons\_halflingsregular') format('svg'); } .glyphicon { position: relative; top: 1px; display: inline-block; font-family: 'Glyphicons Halflings'; font-style: normal; font-weight: normal; line-height: 1; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; } .glyphicon-asterisk:before { content: "\\002a"; } .glyphicon-plus:before { content: "\\002b"; } .glyphicon-euro:before, .glyphicon-eur:before { content: "\\20ac"; } .glyphicon-minus:before { content: "\\2212"; } .glyphicon-cloud:before { content: "\\2601"; } .glyphicon-envelope:before { content: "\\2709"; } .glyphicon-pencil:before { content: "\\270f"; } .glyphicon-glass:before { content: "\\e001"; } .glyphicon-music:before { content: "\\e002"; } .glyphicon-search:before { content: "\\e003"; } .glyphicon-heart:before { content: "\\e005"; } .glyphicon-star:before { content: "\\e006"; } .glyphicon-star-empty:before { content: "\\e007"; } .glyphicon-user:before { content: "\\e008"; } .glyphicon-film:before { content: "\\e009"; } .glyphicon-th-large:before { content: "\\e010"; } .glyphicon-th:before { content: "\\e011"; } .glyphicon-th-list:before { content: "\\e012"; } .glyphicon-ok:before { content: "\\e013"; } .glyphicon-remove:before { content: "\\e014"; } .glyphicon-zoom-in:before { content: "\\e015"; } .glyphicon-zoom-out:before { content: "\\e016"; } .glyphicon-off:before { content: "\\e017"; } .glyphicon-signal:before { content: "\\e018"; } .glyphicon-cog:before { content: "\\e019"; } .glyphicon-trash:before { content: "\\e020"; } .glyphicon-home:before { content: "\\e021"; } .glyphicon-file:before { content: "\\e022"; } .glyphicon-time:before { content: "\\e023"; } .glyphicon-road:before { content: "\\e024"; } .glyphicon-download-alt:before { content: "\\e025"; } .glyphicon-download:before { content: "\\e026"; } .glyphicon-upload:before { content: "\\e027"; } .glyphicon-inbox:before { content: "\\e028"; } .glyphicon-play-circle:before { content: "\\e029"; } .glyphicon-repeat:before { content: "\\e030"; } .glyphicon-refresh:before { content: "\\e031"; } .glyphicon-list-alt:before { content: "\\e032"; } .glyphicon-lock:before { content: "\\e033"; } .glyphicon-flag:before { content: "\\e034"; } .glyphicon-headphones:before { content: "\\e035"; } .glyphicon-volume-off:before { content: "\\e036"; } .glyphicon-volume-down:before { content: "\\e037"; } .glyphicon-volume-up:before { content: "\\e038"; } .glyphicon-qrcode:before { content: "\\e039"; } .glyphicon-barcode:before { content: "\\e040"; } .glyphicon-tag:before { content: "\\e041"; } .glyphicon-tags:before { content: "\\e042"; } .glyphicon-book:before { content: "\\e043"; } .glyphicon-bookmark:before { content: "\\e044"; } .glyphicon-print:before { content: "\\e045"; } .glyphicon-camera:before { content: "\\e046"; } .glyphicon-font:before { content: "\\e047"; } .glyphicon-bold:before { content: "\\e048"; } .glyphicon-italic:before { content: "\\e049"; } .glyphicon-text-height:before { content: "\\e050"; } .glyphicon-text-width:before { content: "\\e051"; } .glyphicon-align-left:before { content: "\\e052"; } .glyphicon-align-center:before { content: "\\e053"; } .glyphicon-align-right:before { content: "\\e054"; } .glyphicon-align-justify:before { content: "\\e055"; } .glyphicon-list:before { content: "\\e056"; } .glyphicon-indent-left:before { content: "\\e057"; } .glyphicon-indent-right:before { content: "\\e058"; } .glyphicon-facetime-video:before { content: "\\e059"; } .glyphicon-picture:before { content: "\\e060"; } .glyphicon-map-marker:before { content: "\\e062"; } .glyphicon-adjust:before { content: "\\e063"; } .glyphicon-tint:before { content: "\\e064"; } .glyphicon-edit:before { content: "\\e065"; } .glyphicon-share:before { content: "\\e066"; } .glyphicon-check:before { content: "\\e067"; } .glyphicon-move:before { content: "\\e068"; } .glyphicon-step-backward:before { content: "\\e069"; } .glyphicon-fast-backward:before { content: "\\e070"; } .glyphicon-backward:before { content: "\\e071"; } .glyphicon-play:before { content: "\\e072"; } .glyphicon-pause:before { content: "\\e073"; } .glyphicon-stop:before { content: "\\e074"; } .glyphicon-forward:before { content: "\\e075"; } .glyphicon-fast-forward:before { content: "\\e076"; } .glyphicon-step-forward:before { content: "\\e077"; } .glyphicon-eject:before { content: "\\e078"; } .glyphicon-chevron-left:before { content: "\\e079"; } .glyphicon-chevron-right:before { content: "\\e080"; } .glyphicon-plus-sign:before { content: "\\e081"; } .glyphicon-minus-sign:before { content: "\\e082"; } .glyphicon-remove-sign:before { content: "\\e083"; } .glyphicon-ok-sign:before { content: "\\e084"; } .glyphicon-question-sign:before { content: "\\e085"; } .glyphicon-info-sign:before { content: "\\e086"; } .glyphicon-screenshot:before { content: "\\e087"; } .glyphicon-remove-circle:before { content: "\\e088"; } .glyphicon-ok-circle:before { content: "\\e089"; } .glyphicon-ban-circle:before { content: "\\e090"; } .glyphicon-arrow-left:before { content: "\\e091"; } .glyphicon-arrow-right:before { content: "\\e092"; } .glyphicon-arrow-up:before { content: "\\e093"; } .glyphicon-arrow-down:before { content: "\\e094"; } .glyphicon-share-alt:before { content: "\\e095"; } .glyphicon-resize-full:before { content: "\\e096"; } .glyphicon-resize-small:before { content: "\\e097"; } .glyphicon-exclamation-sign:before { content: "\\e101"; } .glyphicon-gift:before { content: "\\e102"; } .glyphicon-leaf:before { content: "\\e103"; } .glyphicon-fire:before { content: "\\e104"; } .glyphicon-eye-open:before { content: "\\e105"; } .glyphicon-eye-close:before { content: "\\e106"; } .glyphicon-warning-sign:before { content: "\\e107"; } .glyphicon-plane:before { content: "\\e108"; } .glyphicon-calendar:before { content: "\\e109"; } .glyphicon-random:before { content: "\\e110"; } .glyphicon-comment:before { content: "\\e111"; } .glyphicon-magnet:before { content: "\\e112"; } .glyphicon-chevron-up:before { content: "\\e113"; } .glyphicon-chevron-down:before { content: "\\e114"; } .glyphicon-retweet:before { content: "\\e115"; } .glyphicon-shopping-cart:before { content: "\\e116"; } .glyphicon-folder-close:before { content: "\\e117"; } .glyphicon-folder-open:before { content: "\\e118"; } .glyphicon-resize-vertical:before { content: "\\e119"; } .glyphicon-resize-horizontal:before { content: "\\e120"; } .glyphicon-hdd:before { content: "\\e121"; } .glyphicon-bullhorn:before { content: "\\e122"; } .glyphicon-bell:before { content: "\\e123"; } .glyphicon-certificate:before { content: "\\e124"; } .glyphicon-thumbs-up:before { content: "\\e125"; } .glyphicon-thumbs-down:before { content: "\\e126"; } .glyphicon-hand-right:before { content: "\\e127"; } .glyphicon-hand-left:before { content: "\\e128"; } .glyphicon-hand-up:before { content: "\\e129"; } .glyphicon-hand-down:before { content: "\\e130"; } .glyphicon-circle-arrow-right:before { content: "\\e131"; } .glyphicon-circle-arrow-left:before { content: "\\e132"; } .glyphicon-circle-arrow-up:before { content: "\\e133"; } .glyphicon-circle-arrow-down:before { content: "\\e134"; } .glyphicon-globe:before { content: "\\e135"; } .glyphicon-wrench:before { content: "\\e136"; } .glyphicon-tasks:before { content: "\\e137"; } .glyphicon-filter:before { content: "\\e138"; } .glyphicon-briefcase:before { content: "\\e139"; } .glyphicon-fullscreen:before { content: "\\e140"; } .glyphicon-dashboard:before { content: "\\e141"; } .glyphicon-paperclip:before { content: "\\e142"; } .glyphicon-heart-empty:before { content: "\\e143"; } .glyphicon-link:before { content: "\\e144"; } .glyphicon-phone:before { content: "\\e145"; } .glyphicon-pushpin:before { content: "\\e146"; } .glyphicon-usd:before { content: "\\e148"; } .glyphicon-gbp:before { content: "\\e149"; } .glyphicon-sort:before { content: "\\e150"; } .glyphicon-sort-by-alphabet:before { content: "\\e151"; } .glyphicon-sort-by-alphabet-alt:before { content: "\\e152"; } .glyphicon-sort-by-order:before { content: "\\e153"; } .glyphicon-sort-by-order-alt:before { content: "\\e154"; } .glyphicon-sort-by-attributes:before { content: "\\e155"; } .glyphicon-sort-by-attributes-alt:before { content: "\\e156"; } .glyphicon-unchecked:before { content: "\\e157"; } .glyphicon-expand:before { content: "\\e158"; } .glyphicon-collapse-down:before { content: "\\e159"; } .glyphicon-collapse-up:before { content: "\\e160"; } .glyphicon-log-in:before { content: "\\e161"; } .glyphicon-flash:before { content: "\\e162"; } .glyphicon-log-out:before { content: "\\e163"; } .glyphicon-new-window:before { content: "\\e164"; } .glyphicon-record:before { content: "\\e165"; } .glyphicon-save:before { content: "\\e166"; } .glyphicon-open:before { content: "\\e167"; } .glyphicon-saved:before { content: "\\e168"; } .glyphicon-import:before { content: "\\e169"; } .glyphicon-export:before { content: "\\e170"; } .glyphicon-send:before { content: "\\e171"; } .glyphicon-floppy-disk:before { content: "\\e172"; } .glyphicon-floppy-saved:before { content: "\\e173"; } .glyphicon-floppy-remove:before { content: "\\e174"; } .glyphicon-floppy-save:before { content: "\\e175"; } .glyphicon-floppy-open:before { content: "\\e176"; } .glyphicon-credit-card:before { content: "\\e177"; } .glyphicon-transfer:before { content: "\\e178"; } .glyphicon-cutlery:before { content: "\\e179"; } .glyphicon-header:before { content: "\\e180"; } .glyphicon-compressed:before { content: "\\e181"; } .glyphicon-earphone:before { content: "\\e182"; } .glyphicon-phone-alt:before { content: "\\e183"; } .glyphicon-tower:before { content: "\\e184"; } .glyphicon-stats:before { content: "\\e185"; } .glyphicon-sd-video:before { content: "\\e186"; } .glyphicon-hd-video:before { content: "\\e187"; } .glyphicon-subtitles:before { content: "\\e188"; } .glyphicon-sound-stereo:before { content: "\\e189"; } .glyphicon-sound-dolby:before { content: "\\e190"; } .glyphicon-sound-5-1:before { content: "\\e191"; } .glyphicon-sound-6-1:before { content: "\\e192"; } .glyphicon-sound-7-1:before { content: "\\e193"; } .glyphicon-copyright-mark:before { content: "\\e194"; } .glyphicon-registration-mark:before { content: "\\e195"; } .glyphicon-cloud-download:before { content: "\\e197"; } .glyphicon-cloud-upload:before { content: "\\e198"; } .glyphicon-tree-conifer:before { content: "\\e199"; } .glyphicon-tree-deciduous:before { content: "\\e200"; } .glyphicon-cd:before { content: "\\e201"; } .glyphicon-save-file:before { content: "\\e202"; } .glyphicon-open-file:before { content: "\\e203"; } .glyphicon-level-up:before { content: "\\e204"; } .glyphicon-copy:before { content: "\\e205"; } .glyphicon-paste:before { content: "\\e206"; } .glyphicon-alert:before { content: "\\e209"; } .glyphicon-equalizer:before { content: "\\e210"; } .glyphicon-king:before { content: "\\e211"; } .glyphicon-queen:before { content: "\\e212"; } .glyphicon-pawn:before { content: "\\e213"; } .glyphicon-bishop:before { content: "\\e214"; } .glyphicon-knight:before { content: "\\e215"; } .glyphicon-baby-formula:before { content: "\\e216"; } .glyphicon-tent:before { content: "\\26fa"; } .glyphicon-blackboard:before { content: "\\e218"; } .glyphicon-bed:before { content: "\\e219"; } .glyphicon-apple:before { content: "\\f8ff"; } .glyphicon-erase:before { content: "\\e221"; } .glyphicon-hourglass:before { content: "\\231b"; } .glyphicon-lamp:before { content: "\\e223"; } .glyphicon-duplicate:before { content: "\\e224"; } .glyphicon-piggy-bank:before { content: "\\e225"; } .glyphicon-scissors:before { content: "\\e226"; } .glyphicon-bitcoin:before { content: "\\e227"; } .glyphicon-btc:before { content: "\\e227"; } .glyphicon-xbt:before { content: "\\e227"; } .glyphicon-yen:before { content: "\\00a5"; } .glyphicon-jpy:before { content: "\\00a5"; } .glyphicon-ruble:before { content: "\\20bd"; } .glyphicon-rub:before { content: "\\20bd"; } .glyphicon-scale:before { content: "\\e230"; } .glyphicon-ice-lolly:before { content: "\\e231"; } .glyphicon-ice-lolly-tasted:before { content: "\\e232"; } .glyphicon-education:before { content: "\\e233"; } .glyphicon-option-horizontal:before { content: "\\e234"; } .glyphicon-option-vertical:before { content: "\\e235"; } .glyphicon-menu-hamburger:before { content: "\\e236"; } .glyphicon-modal-window:before { content: "\\e237"; } .glyphicon-oil:before { content: "\\e238"; } .glyphicon-grain:before { content: "\\e239"; } .glyphicon-sunglasses:before { content: "\\e240"; } .glyphicon-text-size:before { content: "\\e241"; } .glyphicon-text-color:before { content: "\\e242"; } .glyphicon-text-background:before { content: "\\e243"; } .glyphicon-object-align-top:before { content: "\\e244"; } .glyphicon-object-align-bottom:before { content: "\\e245"; } .glyphicon-object-align-horizontal:before { content: "\\e246"; } .glyphicon-object-align-left:before { content: "\\e247"; } .glyphicon-object-align-vertical:before { content: "\\e248"; } .glyphicon-object-align-right:before { content: "\\e249"; } .glyphicon-triangle-right:before { content: "\\e250"; } .glyphicon-triangle-left:before { content: "\\e251"; } .glyphicon-triangle-bottom:before { content: "\\e252"; } .glyphicon-triangle-top:before { content: "\\e253"; } .glyphicon-console:before { content: "\\e254"; } .glyphicon-superscript:before { content: "\\e255"; } .glyphicon-subscript:before { content: "\\e256"; } .glyphicon-menu-left:before { content: "\\e257"; } .glyphicon-menu-right:before { content: "\\e258"; } .glyphicon-menu-down:before { content: "\\e259"; } .glyphicon-menu-up:before { content: "\\e260"; } * { -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; } *:before, *:after { -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; } html { font-size: 10px; -webkit-tap-highlight-color: rgba(0, 0, 0, 0); } body { font-family: "Helvetica Neue", Helvetica, Arial, sans-serif; font-size: 13px; line-height: 1.42857143; color: #000; background-color: #fff; } input, button, select, textarea { font-family: inherit; font-size: inherit; line-height: inherit; } a { color: #337ab7; text-decoration: none; } a:hover, a:focus { color: #23527c; text-decoration: underline; } a:focus { outline: 5px auto -webkit-focus-ring-color; outline-offset: -2px; } figure { margin: 0; } img { vertical-align: middle; } .img-responsive, .thumbnail > img, .thumbnail a > img, .carousel-inner > .item > img, .carousel-inner > .item > a > img { display: block; max-width: 100%; height: auto; } .img-rounded { border-radius: 3px; } .img-thumbnail { padding: 4px; line-height: 1.42857143; background-color: #fff; border: 1px solid #ddd; border-radius: 2px; -webkit-transition: all 0.2s ease-in-out; -o-transition: all 0.2s ease-in-out; transition: all 0.2s ease-in-out; display: inline-block; max-width: 100%; height: auto; } .img-circle { border-radius: 50%; } hr { margin-top: 18px; margin-bottom: 18px; border: 0; border-top: 1px solid #eeeeee; } .sr-only { position: absolute; width: 1px; height: 1px; margin: -1px; padding: 0; overflow: hidden; clip: rect(0, 0, 0, 0); border: 0; } .sr-only-focusable:active, .sr-only-focusable:focus { position: static; width: auto; height: auto; margin: 0; overflow: visible; clip: auto; } \[role="button"\] { cursor: pointer; } h1, h2, h3, h4, h5, h6, .h1, .h2, .h3, .h4, .h5, .h6 { font-family: inherit; font-weight: 500; line-height: 1.1; color: inherit; } h1 small, h2 small, h3 small, h4 small, h5 small, h6 small, .h1 small, .h2 small, .h3 small, .h4 small, .h5 small, .h6 small, h1 .small, h2 .small, h3 .small, h4 .small, h5 .small, h6 .small, .h1 .small, .h2 .small, .h3 .small, .h4 .small, .h5 .small, .h6 .small { font-weight: normal; line-height: 1; color: #777777; } h1, .h1, h2, .h2, h3, .h3 { margin-top: 18px; margin-bottom: 9px; } h1 small, .h1 small, h2 small, .h2 small, h3 small, .h3 small, h1 .small, .h1 .small, h2 .small, .h2 .small, h3 .small, .h3 .small { font-size: 65%; } h4, .h4, h5, .h5, h6, .h6 { margin-top: 9px; margin-bottom: 9px; } h4 small, .h4 small, h5 small, .h5 small, h6 small, .h6 small, h4 .small, .h4 .small, h5 .small, .h5 .small, h6 .small, .h6 .small { font-size: 75%; } h1, .h1 { font-size: 33px; } h2, .h2 { font-size: 27px; } h3, .h3 { font-size: 23px; } h4, .h4 { font-size: 17px; } h5, .h5 { font-size: 13px; } h6, .h6 { font-size: 12px; } p { margin: 0 0 9px; } .lead { margin-bottom: 18px; font-size: 14px; font-weight: 300; line-height: 1.4; } @media (min-width: 768px) { .lead { font-size: 19.5px; } } small, .small { font-size: 92%; } mark, .mark { background-color: #fcf8e3; padding: .2em; } .text-left { text-align: left; } .text-right { text-align: right; } .text-center { text-align: center; } .text-justify { text-align: justify; } .text-nowrap { white-space: nowrap; } .text-lowercase { text-transform: lowercase; } .text-uppercase { text-transform: uppercase; } .text-capitalize { text-transform: capitalize; } .text-muted { color: #777777; } .text-primary { color: #337ab7; } a.text-primary:hover, a.text-primary:focus { color: #286090; } .text-success { color: #3c763d; } a.text-success:hover, a.text-success:focus { color: #2b542c; } .text-info { color: #31708f; } a.text-info:hover, a.text-info:focus { color: #245269; } .text-warning { color: #8a6d3b; } a.text-warning:hover, a.text-warning:focus { color: #66512c; } .text-danger { color: #a94442; } a.text-danger:hover, a.text-danger:focus { color: #843534; } .bg-primary { color: #fff; background-color: #337ab7; } a.bg-primary:hover, a.bg-primary:focus { background-color: #286090; } .bg-success { background-color: #dff0d8; } a.bg-success:hover, a.bg-success:focus { background-color: #c1e2b3; } .bg-info { background-color: #d9edf7; } a.bg-info:hover, a.bg-info:focus { background-color: #afd9ee; } .bg-warning { background-color: #fcf8e3; } a.bg-warning:hover, a.bg-warning:focus { background-color: #f7ecb5; } .bg-danger { background-color: #f2dede; } a.bg-danger:hover, a.bg-danger:focus { background-color: #e4b9b9; } .page-header { padding-bottom: 8px; margin: 36px 0 18px; border-bottom: 1px solid #eeeeee; } ul, ol { margin-top: 0; margin-bottom: 9px; } ul ul, ol ul, ul ol, ol ol { margin-bottom: 0; } .list-unstyled { padding-left: 0; list-style: none; } .list-inline { padding-left: 0; list-style: none; margin-left: -5px; } .list-inline > li { display: inline-block; padding-left: 5px; padding-right: 5px; } dl { margin-top: 0; margin-bottom: 18px; } dt, dd { line-height: 1.42857143; } dt { font-weight: bold; } dd { margin-left: 0; } @media (min-width: 541px) { .dl-horizontal dt { float: left; width: 160px; clear: left; text-align: right; overflow: hidden; text-overflow: ellipsis; white-space: nowrap; } .dl-horizontal dd { margin-left: 180px; } } abbr\[title\], abbr\[data-original-title\] { cursor: help; border-bottom: 1px dotted #777777; } .initialism { font-size: 90%; text-transform: uppercase; } blockquote { padding: 9px 18px; margin: 0 0 18px; font-size: inherit; border-left: 5px solid #eeeeee; } blockquote p:last-child, blockquote ul:last-child, blockquote ol:last-child { margin-bottom: 0; } blockquote footer, blockquote small, blockquote .small { display: block; font-size: 80%; line-height: 1.42857143; color: #777777; } blockquote footer:before, blockquote small:before, blockquote .small:before { content: '\\2014 \\00A0'; } .blockquote-reverse, blockquote.pull-right { padding-right: 15px; padding-left: 0; border-right: 5px solid #eeeeee; border-left: 0; text-align: right; } .blockquote-reverse footer:before, blockquote.pull-right footer:before, .blockquote-reverse small:before, blockquote.pull-right small:before, .blockquote-reverse .small:before, blockquote.pull-right .small:before { content: ''; } .blockquote-reverse footer:after, blockquote.pull-right footer:after, .blockquote-reverse small:after, blockquote.pull-right small:after, .blockquote-reverse .small:after, blockquote.pull-right .small:after { content: '\\00A0 \\2014'; } address { margin-bottom: 18px; font-style: normal; line-height: 1.42857143; } code, kbd, pre, samp { font-family: monospace; } code { padding: 2px 4px; font-size: 90%; color: #c7254e; background-color: #f9f2f4; border-radius: 2px; } kbd { padding: 2px 4px; font-size: 90%; color: #888; background-color: transparent; border-radius: 1px; box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25); } kbd kbd { padding: 0; font-size: 100%; font-weight: bold; box-shadow: none; } pre { display: block; padding: 8.5px; margin: 0 0 9px; font-size: 12px; line-height: 1.42857143; word-break: break-all; word-wrap: break-word; color: #333333; background-color: #f5f5f5; border: 1px solid #ccc; border-radius: 2px; } pre code { padding: 0; font-size: inherit; color: inherit; white-space: pre-wrap; background-color: transparent; border-radius: 0; } .pre-scrollable { max-height: 340px; overflow-y: scroll; } .container { margin-right: auto; margin-left: auto; padding-left: 0px; padding-right: 0px; } @media (min-width: 768px) { .container { width: 768px; } } @media (min-width: 992px) { .container { width: 940px; } } @media (min-width: 1200px) { .container { width: 1140px; } } .container-fluid { margin-right: auto; margin-left: auto; padding-left: 0px; padding-right: 0px; } .row { margin-left: 0px; margin-right: 0px; } .col-xs-1, .col-sm-1, .col-md-1, .col-lg-1, .col-xs-2, .col-sm-2, .col-md-2, .col-lg-2, .col-xs-3, .col-sm-3, .col-md-3, .col-lg-3, .col-xs-4, .col-sm-4, .col-md-4, .col-lg-4, .col-xs-5, .col-sm-5, .col-md-5, .col-lg-5, .col-xs-6, .col-sm-6, .col-md-6, .col-lg-6, .col-xs-7, .col-sm-7, .col-md-7, .col-lg-7, .col-xs-8, .col-sm-8, .col-md-8, .col-lg-8, .col-xs-9, .col-sm-9, .col-md-9, .col-lg-9, .col-xs-10, .col-sm-10, .col-md-10, .col-lg-10, .col-xs-11, .col-sm-11, .col-md-11, .col-lg-11, .col-xs-12, .col-sm-12, .col-md-12, .col-lg-12 { position: relative; min-height: 1px; padding-left: 0px; padding-right: 0px; } .col-xs-1, .col-xs-2, .col-xs-3, .col-xs-4, .col-xs-5, .col-xs-6, .col-xs-7, .col-xs-8, .col-xs-9, .col-xs-10, .col-xs-11, .col-xs-12 { float: left; } .col-xs-12 { width: 100%; } .col-xs-11 { width: 91.66666667%; } .col-xs-10 { width: 83.33333333%; } .col-xs-9 { width: 75%; } .col-xs-8 { width: 66.66666667%; } .col-xs-7 { width: 58.33333333%; } .col-xs-6 { width: 50%; } .col-xs-5 { width: 41.66666667%; } .col-xs-4 { width: 33.33333333%; } .col-xs-3 { width: 25%; } .col-xs-2 { width: 16.66666667%; } .col-xs-1 { width: 8.33333333%; } .col-xs-pull-12 { right: 100%; } .col-xs-pull-11 { right: 91.66666667%; } .col-xs-pull-10 { right: 83.33333333%; } .col-xs-pull-9 { right: 75%; } .col-xs-pull-8 { right: 66.66666667%; } .col-xs-pull-7 { right: 58.33333333%; } .col-xs-pull-6 { right: 50%; } .col-xs-pull-5 { right: 41.66666667%; } .col-xs-pull-4 { right: 33.33333333%; } .col-xs-pull-3 { right: 25%; } .col-xs-pull-2 { right: 16.66666667%; } .col-xs-pull-1 { right: 8.33333333%; } .col-xs-pull-0 { right: auto; } .col-xs-push-12 { left: 100%; } .col-xs-push-11 { left: 91.66666667%; } .col-xs-push-10 { left: 83.33333333%; } .col-xs-push-9 { left: 75%; } .col-xs-push-8 { left: 66.66666667%; } .col-xs-push-7 { left: 58.33333333%; } .col-xs-push-6 { left: 50%; } .col-xs-push-5 { left: 41.66666667%; } .col-xs-push-4 { left: 33.33333333%; } .col-xs-push-3 { left: 25%; } .col-xs-push-2 { left: 16.66666667%; } .col-xs-push-1 { left: 8.33333333%; } .col-xs-push-0 { left: auto; } .col-xs-offset-12 { margin-left: 100%; } .col-xs-offset-11 { margin-left: 91.66666667%; } .col-xs-offset-10 { margin-left: 83.33333333%; } .col-xs-offset-9 { margin-left: 75%; } .col-xs-offset-8 { margin-left: 66.66666667%; } .col-xs-offset-7 { margin-left: 58.33333333%; } .col-xs-offset-6 { margin-left: 50%; } .col-xs-offset-5 { margin-left: 41.66666667%; } .col-xs-offset-4 { margin-left: 33.33333333%; } .col-xs-offset-3 { margin-left: 25%; } .col-xs-offset-2 { margin-left: 16.66666667%; } .col-xs-offset-1 { margin-left: 8.33333333%; } .col-xs-offset-0 { margin-left: 0%; } @media (min-width: 768px) { .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 { float: left; } .col-sm-12 { width: 100%; } .col-sm-11 { width: 91.66666667%; } .col-sm-10 { width: 83.33333333%; } .col-sm-9 { width: 75%; } .col-sm-8 { width: 66.66666667%; } .col-sm-7 { width: 58.33333333%; } .col-sm-6 { width: 50%; } .col-sm-5 { width: 41.66666667%; } .col-sm-4 { width: 33.33333333%; } .col-sm-3 { width: 25%; } .col-sm-2 { width: 16.66666667%; } .col-sm-1 { width: 8.33333333%; } .col-sm-pull-12 { right: 100%; } .col-sm-pull-11 { right: 91.66666667%; } .col-sm-pull-10 { right: 83.33333333%; } .col-sm-pull-9 { right: 75%; } .col-sm-pull-8 { right: 66.66666667%; } .col-sm-pull-7 { right: 58.33333333%; } .col-sm-pull-6 { right: 50%; } .col-sm-pull-5 { right: 41.66666667%; } .col-sm-pull-4 { right: 33.33333333%; } .col-sm-pull-3 { right: 25%; } .col-sm-pull-2 { right: 16.66666667%; } .col-sm-pull-1 { right: 8.33333333%; } .col-sm-pull-0 { right: auto; } .col-sm-push-12 { left: 100%; } .col-sm-push-11 { left: 91.66666667%; } .col-sm-push-10 { left: 83.33333333%; } .col-sm-push-9 { left: 75%; } .col-sm-push-8 { left: 66.66666667%; } .col-sm-push-7 { left: 58.33333333%; } .col-sm-push-6 { left: 50%; } .col-sm-push-5 { left: 41.66666667%; } .col-sm-push-4 { left: 33.33333333%; } .col-sm-push-3 { left: 25%; } .col-sm-push-2 { left: 16.66666667%; } .col-sm-push-1 { left: 8.33333333%; } .col-sm-push-0 { left: auto; } .col-sm-offset-12 { margin-left: 100%; } .col-sm-offset-11 { margin-left: 91.66666667%; } .col-sm-offset-10 { margin-left: 83.33333333%; } .col-sm-offset-9 { margin-left: 75%; } .col-sm-offset-8 { margin-left: 66.66666667%; } .col-sm-offset-7 { margin-left: 58.33333333%; } .col-sm-offset-6 { margin-left: 50%; } .col-sm-offset-5 { margin-left: 41.66666667%; } .col-sm-offset-4 { margin-left: 33.33333333%; } .col-sm-offset-3 { margin-left: 25%; } .col-sm-offset-2 { margin-left: 16.66666667%; } .col-sm-offset-1 { margin-left: 8.33333333%; } .col-sm-offset-0 { margin-left: 0%; } } @media (min-width: 992px) { .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 { float: left; } .col-md-12 { width: 100%; } .col-md-11 { width: 91.66666667%; } .col-md-10 { width: 83.33333333%; } .col-md-9 { width: 75%; } .col-md-8 { width: 66.66666667%; } .col-md-7 { width: 58.33333333%; } .col-md-6 { width: 50%; } .col-md-5 { width: 41.66666667%; } .col-md-4 { width: 33.33333333%; } .col-md-3 { width: 25%; } .col-md-2 { width: 16.66666667%; } .col-md-1 { width: 8.33333333%; } .col-md-pull-12 { right: 100%; } .col-md-pull-11 { right: 91.66666667%; } .col-md-pull-10 { right: 83.33333333%; } .col-md-pull-9 { right: 75%; } .col-md-pull-8 { right: 66.66666667%; } .col-md-pull-7 { right: 58.33333333%; } .col-md-pull-6 { right: 50%; } .col-md-pull-5 { right: 41.66666667%; } .col-md-pull-4 { right: 33.33333333%; } .col-md-pull-3 { right: 25%; } .col-md-pull-2 { right: 16.66666667%; } .col-md-pull-1 { right: 8.33333333%; } .col-md-pull-0 { right: auto; } .col-md-push-12 { left: 100%; } .col-md-push-11 { left: 91.66666667%; } .col-md-push-10 { left: 83.33333333%; } .col-md-push-9 { left: 75%; } .col-md-push-8 { left: 66.66666667%; } .col-md-push-7 { left: 58.33333333%; } .col-md-push-6 { left: 50%; } .col-md-push-5 { left: 41.66666667%; } .col-md-push-4 { left: 33.33333333%; } .col-md-push-3 { left: 25%; } .col-md-push-2 { left: 16.66666667%; } .col-md-push-1 { left: 8.33333333%; } .col-md-push-0 { left: auto; } .col-md-offset-12 { margin-left: 100%; } .col-md-offset-11 { margin-left: 91.66666667%; } .col-md-offset-10 { margin-left: 83.33333333%; } .col-md-offset-9 { margin-left: 75%; } .col-md-offset-8 { margin-left: 66.66666667%; } .col-md-offset-7 { margin-left: 58.33333333%; } .col-md-offset-6 { margin-left: 50%; } .col-md-offset-5 { margin-left: 41.66666667%; } .col-md-offset-4 { margin-left: 33.33333333%; } .col-md-offset-3 { margin-left: 25%; } .col-md-offset-2 { margin-left: 16.66666667%; } .col-md-offset-1 { margin-left: 8.33333333%; } .col-md-offset-0 { margin-left: 0%; } } @media (min-width: 1200px) { .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 { float: left; } .col-lg-12 { width: 100%; } .col-lg-11 { width: 91.66666667%; } .col-lg-10 { width: 83.33333333%; } .col-lg-9 { width: 75%; } .col-lg-8 { width: 66.66666667%; } .col-lg-7 { width: 58.33333333%; } .col-lg-6 { width: 50%; } .col-lg-5 { width: 41.66666667%; } .col-lg-4 { width: 33.33333333%; } .col-lg-3 { width: 25%; } .col-lg-2 { width: 16.66666667%; } .col-lg-1 { width: 8.33333333%; } .col-lg-pull-12 { right: 100%; } .col-lg-pull-11 { right: 91.66666667%; } .col-lg-pull-10 { right: 83.33333333%; } .col-lg-pull-9 { right: 75%; } .col-lg-pull-8 { right: 66.66666667%; } .col-lg-pull-7 { right: 58.33333333%; } .col-lg-pull-6 { right: 50%; } .col-lg-pull-5 { right: 41.66666667%; } .col-lg-pull-4 { right: 33.33333333%; } .col-lg-pull-3 { right: 25%; } .col-lg-pull-2 { right: 16.66666667%; } .col-lg-pull-1 { right: 8.33333333%; } .col-lg-pull-0 { right: auto; } .col-lg-push-12 { left: 100%; } .col-lg-push-11 { left: 91.66666667%; } .col-lg-push-10 { left: 83.33333333%; } .col-lg-push-9 { left: 75%; } .col-lg-push-8 { left: 66.66666667%; } .col-lg-push-7 { left: 58.33333333%; } .col-lg-push-6 { left: 50%; } .col-lg-push-5 { left: 41.66666667%; } .col-lg-push-4 { left: 33.33333333%; } .col-lg-push-3 { left: 25%; } .col-lg-push-2 { left: 16.66666667%; } .col-lg-push-1 { left: 8.33333333%; } .col-lg-push-0 { left: auto; } .col-lg-offset-12 { margin-left: 100%; } .col-lg-offset-11 { margin-left: 91.66666667%; } .col-lg-offset-10 { margin-left: 83.33333333%; } .col-lg-offset-9 { margin-left: 75%; } .col-lg-offset-8 { margin-left: 66.66666667%; } .col-lg-offset-7 { margin-left: 58.33333333%; } .col-lg-offset-6 { margin-left: 50%; } .col-lg-offset-5 { margin-left: 41.66666667%; } .col-lg-offset-4 { margin-left: 33.33333333%; } .col-lg-offset-3 { margin-left: 25%; } .col-lg-offset-2 { margin-left: 16.66666667%; } .col-lg-offset-1 { margin-left: 8.33333333%; } .col-lg-offset-0 { margin-left: 0%; } } table { background-color: transparent; } caption { padding-top: 8px; padding-bottom: 8px; color: #777777; text-align: left; } th { text-align: left; } .table { width: 100%; max-width: 100%; margin-bottom: 18px; } .table > thead > tr > th, .table > tbody > tr > th, .table > tfoot > tr > th, .table > thead > tr > td, .table > tbody > tr > td, .table > tfoot > tr > td { padding: 8px; line-height: 1.42857143; vertical-align: top; border-top: 1px solid #ddd; } .table > thead > tr > th { vertical-align: bottom; border-bottom: 2px solid #ddd; } .table > caption + thead > tr:first-child > th, .table > colgroup + thead > tr:first-child > th, .table > thead:first-child > tr:first-child > th, .table > caption + thead > tr:first-child > td, .table > colgroup + thead > tr:first-child > td, .table > thead:first-child > tr:first-child > td { border-top: 0; } .table > tbody + tbody { border-top: 2px solid #ddd; } .table .table { background-color: #fff; } .table-condensed > thead > tr > th, .table-condensed > tbody > tr > th, .table-condensed > tfoot > tr > th, .table-condensed > thead > tr > td, .table-condensed > tbody > tr > td, .table-condensed > tfoot > tr > td { padding: 5px; } .table-bordered { border: 1px solid #ddd; } .table-bordered > thead > tr > th, .table-bordered > tbody > tr > th, .table-bordered > tfoot > tr > th, .table-bordered > thead > tr > td, .table-bordered > tbody > tr > td, .table-bordered > tfoot > tr > td { border: 1px solid #ddd; } .table-bordered > thead > tr > th, .table-bordered > thead > tr > td { border-bottom-width: 2px; } .table-striped > tbody > tr:nth-of-type(odd) { background-color: #f9f9f9; } .table-hover > tbody > tr:hover { background-color: #f5f5f5; } table col\[class*="col-"\] { position: static; float: none; display: table-column; } table td\[class*="col-"\], table th\[class*="col-"\] { position: static; float: none; display: table-cell; } .table > thead > tr > td.active, .table > tbody > tr > td.active, .table > tfoot > tr > td.active, .table > thead > tr > th.active, .table > tbody > tr > th.active, .table > tfoot > tr > th.active, .table > thead > tr.active > td, .table > tbody > tr.active > td, .table > tfoot > tr.active > td, .table > thead > tr.active > th, .table > tbody > tr.active > th, .table > tfoot > tr.active > th { background-color: #f5f5f5; } .table-hover > tbody > tr > td.active:hover, .table-hover > tbody > tr > th.active:hover, .table-hover > tbody > tr.active:hover > td, .table-hover > tbody > tr:hover > .active, .table-hover > tbody > tr.active:hover > th { background-color: #e8e8e8; } .table > thead > tr > td.success, .table > tbody > tr > td.success, .table > tfoot > tr > td.success, .table > thead > tr > th.success, .table > tbody > tr > th.success, .table > tfoot > tr > th.success, .table > thead > tr.success > td, .table > tbody > tr.success > td, .table > tfoot > tr.success > td, .table > thead > tr.success > th, .table > tbody > tr.success > th, .table > tfoot > tr.success > th { background-color: #dff0d8; } .table-hover > tbody > tr > td.success:hover, .table-hover > tbody > tr > th.success:hover, .table-hover > tbody > tr.success:hover > td, .table-hover > tbody > tr:hover > .success, .table-hover > tbody > tr.success:hover > th { background-color: #d0e9c6; } .table > thead > tr > td.info, .table > tbody > tr > td.info, .table > tfoot > tr > td.info, .table > thead > tr > th.info, .table > tbody > tr > th.info, .table > tfoot > tr > th.info, .table > thead > tr.info > td, .table > tbody > tr.info > td, .table > tfoot > tr.info > td, .table > thead > tr.info > th, .table > tbody > tr.info > th, .table > tfoot > tr.info > th { background-color: #d9edf7; } .table-hover > tbody > tr > td.info:hover, .table-hover > tbody > tr > th.info:hover, .table-hover > tbody > tr.info:hover > td, .table-hover > tbody > tr:hover > .info, .table-hover > tbody > tr.info:hover > th { background-color: #c4e3f3; } .table > thead > tr > td.warning, .table > tbody > tr > td.warning, .table > tfoot > tr > td.warning, .table > thead > tr > th.warning, .table > tbody > tr > th.warning, .table > tfoot > tr > th.warning, .table > thead > tr.warning > td, .table > tbody > tr.warning > td, .table > tfoot > tr.warning > td, .table > thead > tr.warning > th, .table > tbody > tr.warning > th, .table > tfoot > tr.warning > th { background-color: #fcf8e3; } .table-hover > tbody > tr > td.warning:hover, .table-hover > tbody > tr > th.warning:hover, .table-hover > tbody > tr.warning:hover > td, .table-hover > tbody > tr:hover > .warning, .table-hover > tbody > tr.warning:hover > th { background-color: #faf2cc; } .table > thead > tr > td.danger, .table > tbody > tr > td.danger, .table > tfoot > tr > td.danger, .table > thead > tr > th.danger, .table > tbody > tr > th.danger, .table > tfoot > tr > th.danger, .table > thead > tr.danger > td, .table > tbody > tr.danger > td, .table > tfoot > tr.danger > td, .table > thead > tr.danger > th, .table > tbody > tr.danger > th, .table > tfoot > tr.danger > th { background-color: #f2dede; } .table-hover > tbody > tr > td.danger:hover, .table-hover > tbody > tr > th.danger:hover, .table-hover > tbody > tr.danger:hover > td, .table-hover > tbody > tr:hover > .danger, .table-hover > tbody > tr.danger:hover > th { background-color: #ebcccc; } .table-responsive { overflow-x: auto; min-height: 0.01%; } @media screen and (max-width: 767px) { .table-responsive { width: 100%; margin-bottom: 13.5px; overflow-y: hidden; -ms-overflow-style: -ms-autohiding-scrollbar; border: 1px solid #ddd; } .table-responsive > .table { margin-bottom: 0; } .table-responsive > .table > thead > tr > th, .table-responsive > .table > tbody > tr > th, .table-responsive > .table > tfoot > tr > th, .table-responsive > .table > thead > tr > td, .table-responsive > .table > tbody > tr > td, .table-responsive > .table > tfoot > tr > td { white-space: nowrap; } .table-responsive > .table-bordered { border: 0; } .table-responsive > .table-bordered > thead > tr > th:first-child, .table-responsive > .table-bordered > tbody > tr > th:first-child, .table-responsive > .table-bordered > tfoot > tr > th:first-child, .table-responsive > .table-bordered > thead > tr > td:first-child, .table-responsive > .table-bordered > tbody > tr > td:first-child, .table-responsive > .table-bordered > tfoot > tr > td:first-child { border-left: 0; } .table-responsive > .table-bordered > thead > tr > th:last-child, .table-responsive > .table-bordered > tbody > tr > th:last-child, .table-responsive > .table-bordered > tfoot > tr > th:last-child, .table-responsive > .table-bordered > thead > tr > td:last-child, .table-responsive > .table-bordered > tbody > tr > td:last-child, .table-responsive > .table-bordered > tfoot > tr > td:last-child { border-right: 0; } .table-responsive > .table-bordered > tbody > tr:last-child > th, .table-responsive > .table-bordered > tfoot > tr:last-child > th, .table-responsive > .table-bordered > tbody > tr:last-child > td, .table-responsive > .table-bordered > tfoot > tr:last-child > td { border-bottom: 0; } } fieldset { padding: 0; margin: 0; border: 0; min-width: 0; } legend { display: block; width: 100%; padding: 0; margin-bottom: 18px; font-size: 19.5px; line-height: inherit; color: #333333; border: 0; border-bottom: 1px solid #e5e5e5; } label { display: inline-block; max-width: 100%; margin-bottom: 5px; font-weight: bold; } input\[type="search"\] { -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; } input\[type="radio"\], input\[type="checkbox"\] { margin: 4px 0 0; margin-top: 1px \\9; line-height: normal; } input\[type="file"\] { display: block; } input\[type="range"\] { display: block; width: 100%; } select\[multiple\], select\[size\] { height: auto; } input\[type="file"\]:focus, input\[type="radio"\]:focus, input\[type="checkbox"\]:focus { outline: 5px auto -webkit-focus-ring-color; outline-offset: -2px; } output { display: block; padding-top: 7px; font-size: 13px; line-height: 1.42857143; color: #555555; } .form-control { display: block; width: 100%; height: 32px; padding: 6px 12px; font-size: 13px; line-height: 1.42857143; color: #555555; background-color: #fff; background-image: none; border: 1px solid #ccc; border-radius: 2px; -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075); box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075); -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s; -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s; transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s; } .form-control:focus { border-color: #66afe9; outline: 0; -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6); box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6); } .form-control::-moz-placeholder { color: #999; opacity: 1; } .form-control:-ms-input-placeholder { color: #999; } .form-control::-webkit-input-placeholder { color: #999; } .form-control::-ms-expand { border: 0; background-color: transparent; } .form-control\[disabled\], .form-control\[readonly\], fieldset\[disabled\] .form-control { background-color: #eeeeee; opacity: 1; } .form-control\[disabled\], fieldset\[disabled\] .form-control { cursor: not-allowed; } textarea.form-control { height: auto; } input\[type="search"\] { -webkit-appearance: none; } @media screen and (-webkit-min-device-pixel-ratio: 0) { input\[type="date"\].form-control, input\[type="time"\].form-control, input\[type="datetime-local"\].form-control, input\[type="month"\].form-control { line-height: 32px; } input\[type="date"\].input-sm, input\[type="time"\].input-sm, input\[type="datetime-local"\].input-sm, input\[type="month"\].input-sm, .input-group-sm input\[type="date"\], .input-group-sm input\[type="time"\], .input-group-sm input\[type="datetime-local"\], .input-group-sm input\[type="month"\] { line-height: 30px; } input\[type="date"\].input-lg, input\[type="time"\].input-lg, input\[type="datetime-local"\].input-lg, input\[type="month"\].input-lg, .input-group-lg input\[type="date"\], .input-group-lg input\[type="time"\], .input-group-lg input\[type="datetime-local"\], .input-group-lg input\[type="month"\] { line-height: 45px; } } .form-group { margin-bottom: 15px; } .radio, .checkbox { position: relative; display: block; margin-top: 10px; margin-bottom: 10px; } .radio label, .checkbox label { min-height: 18px; padding-left: 20px; margin-bottom: 0; font-weight: normal; cursor: pointer; } .radio input\[type="radio"\], .radio-inline input\[type="radio"\], .checkbox input\[type="checkbox"\], .checkbox-inline input\[type="checkbox"\] { position: absolute; margin-left: -20px; margin-top: 4px \\9; } .radio + .radio, .checkbox + .checkbox { margin-top: -5px; } .radio-inline, .checkbox-inline { position: relative; display: inline-block; padding-left: 20px; margin-bottom: 0; vertical-align: middle; font-weight: normal; cursor: pointer; } .radio-inline + .radio-inline, .checkbox-inline + .checkbox-inline { margin-top: 0; margin-left: 10px; } input\[type="radio"\]\[disabled\], input\[type="checkbox"\]\[disabled\], input\[type="radio"\].disabled, input\[type="checkbox"\].disabled, fieldset\[disabled\] input\[type="radio"\], fieldset\[disabled\] input\[type="checkbox"\] { cursor: not-allowed; } .radio-inline.disabled, .checkbox-inline.disabled, fieldset\[disabled\] .radio-inline, fieldset\[disabled\] .checkbox-inline { cursor: not-allowed; } .radio.disabled label, .checkbox.disabled label, fieldset\[disabled\] .radio label, fieldset\[disabled\] .checkbox label { cursor: not-allowed; } .form-control-static { padding-top: 7px; padding-bottom: 7px; margin-bottom: 0; min-height: 31px; } .form-control-static.input-lg, .form-control-static.input-sm { padding-left: 0; padding-right: 0; } .input-sm { height: 30px; padding: 5px 10px; font-size: 12px; line-height: 1.5; border-radius: 1px; } select.input-sm { height: 30px; line-height: 30px; } textarea.input-sm, select\[multiple\].input-sm { height: auto; } .form-group-sm .form-control { height: 30px; padding: 5px 10px; font-size: 12px; line-height: 1.5; border-radius: 1px; } .form-group-sm select.form-control { height: 30px; line-height: 30px; } .form-group-sm textarea.form-control, .form-group-sm select\[multiple\].form-control { height: auto; } .form-group-sm .form-control-static { height: 30px; min-height: 30px; padding: 6px 10px; font-size: 12px; line-height: 1.5; } .input-lg { height: 45px; padding: 10px 16px; font-size: 17px; line-height: 1.3333333; border-radius: 3px; } select.input-lg { height: 45px; line-height: 45px; } textarea.input-lg, select\[multiple\].input-lg { height: auto; } .form-group-lg .form-control { height: 45px; padding: 10px 16px; font-size: 17px; line-height: 1.3333333; border-radius: 3px; } .form-group-lg select.form-control { height: 45px; line-height: 45px; } .form-group-lg textarea.form-control, .form-group-lg select\[multiple\].form-control { height: auto; } .form-group-lg .form-control-static { height: 45px; min-height: 35px; padding: 11px 16px; font-size: 17px; line-height: 1.3333333; } .has-feedback { position: relative; } .has-feedback .form-control { padding-right: 40px; } .form-control-feedback { position: absolute; top: 0; right: 0; z-index: 2; display: block; width: 32px; height: 32px; line-height: 32px; text-align: center; pointer-events: none; } .input-lg + .form-control-feedback, .input-group-lg + .form-control-feedback, .form-group-lg .form-control + .form-control-feedback { width: 45px; height: 45px; line-height: 45px; } .input-sm + .form-control-feedback, .input-group-sm + .form-control-feedback, .form-group-sm .form-control + .form-control-feedback { width: 30px; height: 30px; line-height: 30px; } .has-success .help-block, .has-success .control-label, .has-success .radio, .has-success .checkbox, .has-success .radio-inline, .has-success .checkbox-inline, .has-success.radio label, .has-success.checkbox label, .has-success.radio-inline label, .has-success.checkbox-inline label { color: #3c763d; } .has-success .form-control { border-color: #3c763d; -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075); box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075); } .has-success .form-control:focus { border-color: #2b542c; -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168; box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168; } .has-success .input-group-addon { color: #3c763d; border-color: #3c763d; background-color: #dff0d8; } .has-success .form-control-feedback { color: #3c763d; } .has-warning .help-block, .has-warning .control-label, .has-warning .radio, .has-warning .checkbox, .has-warning .radio-inline, .has-warning .checkbox-inline, .has-warning.radio label, .has-warning.checkbox label, .has-warning.radio-inline label, .has-warning.checkbox-inline label { color: #8a6d3b; } .has-warning .form-control { border-color: #8a6d3b; -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075); box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075); } .has-warning .form-control:focus { border-color: #66512c; -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b; box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b; } .has-warning .input-group-addon { color: #8a6d3b; border-color: #8a6d3b; background-color: #fcf8e3; } .has-warning .form-control-feedback { color: #8a6d3b; } .has-error .help-block, .has-error .control-label, .has-error .radio, .has-error .checkbox, .has-error .radio-inline, .has-error .checkbox-inline, .has-error.radio label, .has-error.checkbox label, .has-error.radio-inline label, .has-error.checkbox-inline label { color: #a94442; } .has-error .form-control { border-color: #a94442; -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075); box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075); } .has-error .form-control:focus { border-color: #843534; -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483; box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483; } .has-error .input-group-addon { color: #a94442; border-color: #a94442; background-color: #f2dede; } .has-error .form-control-feedback { color: #a94442; } .has-feedback label ~ .form-control-feedback { top: 23px; } .has-feedback label.sr-only ~ .form-control-feedback { top: 0; } .help-block { display: block; margin-top: 5px; margin-bottom: 10px; color: #404040; } @media (min-width: 768px) { .form-inline .form-group { display: inline-block; margin-bottom: 0; vertical-align: middle; } .form-inline .form-control { display: inline-block; width: auto; vertical-align: middle; } .form-inline .form-control-static { display: inline-block; } .form-inline .input-group { display: inline-table; vertical-align: middle; } .form-inline .input-group .input-group-addon, .form-inline .input-group .input-group-btn, .form-inline .input-group .form-control { width: auto; } .form-inline .input-group > .form-control { width: 100%; } .form-inline .control-label { margin-bottom: 0; vertical-align: middle; } .form-inline .radio, .form-inline .checkbox { display: inline-block; margin-top: 0; margin-bottom: 0; vertical-align: middle; } .form-inline .radio label, .form-inline .checkbox label { padding-left: 0; } .form-inline .radio input\[type="radio"\], .form-inline .checkbox input\[type="checkbox"\] { position: relative; margin-left: 0; } .form-inline .has-feedback .form-control-feedback { top: 0; } } .form-horizontal .radio, .form-horizontal .checkbox, .form-horizontal .radio-inline, .form-horizontal .checkbox-inline { margin-top: 0; margin-bottom: 0; padding-top: 7px; } .form-horizontal .radio, .form-horizontal .checkbox { min-height: 25px; } .form-horizontal .form-group { margin-left: 0px; margin-right: 0px; } @media (min-width: 768px) { .form-horizontal .control-label { text-align: right; margin-bottom: 0; padding-top: 7px; } } .form-horizontal .has-feedback .form-control-feedback { right: 0px; } @media (min-width: 768px) { .form-horizontal .form-group-lg .control-label { padding-top: 11px; font-size: 17px; } } @media (min-width: 768px) { .form-horizontal .form-group-sm .control-label { padding-top: 6px; font-size: 12px; } } .btn { display: inline-block; margin-bottom: 0; font-weight: normal; text-align: center; vertical-align: middle; touch-action: manipulation; cursor: pointer; background-image: none; border: 1px solid transparent; white-space: nowrap; padding: 6px 12px; font-size: 13px; line-height: 1.42857143; border-radius: 2px; -webkit-user-select: none; -moz-user-select: none; -ms-user-select: none; user-select: none; } .btn:focus, .btn:active:focus, .btn.active:focus, .btn.focus, .btn:active.focus, .btn.active.focus { outline: 5px auto -webkit-focus-ring-color; outline-offset: -2px; } .btn:hover, .btn:focus, .btn.focus { color: #333; text-decoration: none; } .btn:active, .btn.active { outline: 0; background-image: none; -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125); box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125); } .btn.disabled, .btn\[disabled\], fieldset\[disabled\] .btn { cursor: not-allowed; opacity: 0.65; filter: alpha(opacity=65); -webkit-box-shadow: none; box-shadow: none; } a.btn.disabled, fieldset\[disabled\] a.btn { pointer-events: none; } .btn-default { color: #333; background-color: #fff; border-color: #ccc; } .btn-default:focus, .btn-default.focus { color: #333; background-color: #e6e6e6; border-color: #8c8c8c; } .btn-default:hover { color: #333; background-color: #e6e6e6; border-color: #adadad; } .btn-default:active, .btn-default.active, .open > .dropdown-toggle.btn-default { color: #333; background-color: #e6e6e6; border-color: #adadad; } .btn-default:active:hover, .btn-default.active:hover, .open > .dropdown-toggle.btn-default:hover, .btn-default:active:focus, .btn-default.active:focus, .open > .dropdown-toggle.btn-default:focus, .btn-default:active.focus, .btn-default.active.focus, .open > .dropdown-toggle.btn-default.focus { color: #333; background-color: #d4d4d4; border-color: #8c8c8c; } .btn-default:active, .btn-default.active, .open > .dropdown-toggle.btn-default { background-image: none; } .btn-default.disabled:hover, .btn-default\[disabled\]:hover, fieldset\[disabled\] .btn-default:hover, .btn-default.disabled:focus, .btn-default\[disabled\]:focus, fieldset\[disabled\] .btn-default:focus, .btn-default.disabled.focus, .btn-default\[disabled\].focus, fieldset\[disabled\] .btn-default.focus { background-color: #fff; border-color: #ccc; } .btn-default .badge { color: #fff; background-color: #333; } .btn-primary { color: #fff; background-color: #337ab7; border-color: #2e6da4; } .btn-primary:focus, .btn-primary.focus { color: #fff; background-color: #286090; border-color: #122b40; } .btn-primary:hover { color: #fff; background-color: #286090; border-color: #204d74; } .btn-primary:active, .btn-primary.active, .open > .dropdown-toggle.btn-primary { color: #fff; background-color: #286090; border-color: #204d74; } .btn-primary:active:hover, .btn-primary.active:hover, .open > .dropdown-toggle.btn-primary:hover, .btn-primary:active:focus, .btn-primary.active:focus, .open > .dropdown-toggle.btn-primary:focus, .btn-primary:active.focus, .btn-primary.active.focus, .open > .dropdown-toggle.btn-primary.focus { color: #fff; background-color: #204d74; border-color: #122b40; } .btn-primary:active, .btn-primary.active, .open > .dropdown-toggle.btn-primary { background-image: none; } .btn-primary.disabled:hover, .btn-primary\[disabled\]:hover, fieldset\[disabled\] .btn-primary:hover, .btn-primary.disabled:focus, .btn-primary\[disabled\]:focus, fieldset\[disabled\] .btn-primary:focus, .btn-primary.disabled.focus, .btn-primary\[disabled\].focus, fieldset\[disabled\] .btn-primary.focus { background-color: #337ab7; border-color: #2e6da4; } .btn-primary .badge { color: #337ab7; background-color: #fff; } .btn-success { color: #fff; background-color: #5cb85c; border-color: #4cae4c; } .btn-success:focus, .btn-success.focus { color: #fff; background-color: #449d44; border-color: #255625; } .btn-success:hover { color: #fff; background-color: #449d44; border-color: #398439; } .btn-success:active, .btn-success.active, .open > .dropdown-toggle.btn-success { color: #fff; background-color: #449d44; border-color: #398439; } .btn-success:active:hover, .btn-success.active:hover, .open > .dropdown-toggle.btn-success:hover, .btn-success:active:focus, .btn-success.active:focus, .open > .dropdown-toggle.btn-success:focus, .btn-success:active.focus, .btn-success.active.focus, .open > .dropdown-toggle.btn-success.focus { color: #fff; background-color: #398439; border-color: #255625; } .btn-success:active, .btn-success.active, .open > .dropdown-toggle.btn-success { background-image: none; } .btn-success.disabled:hover, .btn-success\[disabled\]:hover, fieldset\[disabled\] .btn-success:hover, .btn-success.disabled:focus, .btn-success\[disabled\]:focus, fieldset\[disabled\] .btn-success:focus, .btn-success.disabled.focus, .btn-success\[disabled\].focus, fieldset\[disabled\] .btn-success.focus { background-color: #5cb85c; border-color: #4cae4c; } .btn-success .badge { color: #5cb85c; background-color: #fff; } .btn-info { color: #fff; background-color: #5bc0de; border-color: #46b8da; } .btn-info:focus, .btn-info.focus { color: #fff; background-color: #31b0d5; border-color: #1b6d85; } .btn-info:hover { color: #fff; background-color: #31b0d5; border-color: #269abc; } .btn-info:active, .btn-info.active, .open > .dropdown-toggle.btn-info { color: #fff; background-color: #31b0d5; border-color: #269abc; } .btn-info:active:hover, .btn-info.active:hover, .open > .dropdown-toggle.btn-info:hover, .btn-info:active:focus, .btn-info.active:focus, .open > .dropdown-toggle.btn-info:focus, .btn-info:active.focus, .btn-info.active.focus, .open > .dropdown-toggle.btn-info.focus { color: #fff; background-color: #269abc; border-color: #1b6d85; } .btn-info:active, .btn-info.active, .open > .dropdown-toggle.btn-info { background-image: none; } .btn-info.disabled:hover, .btn-info\[disabled\]:hover, fieldset\[disabled\] .btn-info:hover, .btn-info.disabled:focus, .btn-info\[disabled\]:focus, fieldset\[disabled\] .btn-info:focus, .btn-info.disabled.focus, .btn-info\[disabled\].focus, fieldset\[disabled\] .btn-info.focus { background-color: #5bc0de; border-color: #46b8da; } .btn-info .badge { color: #5bc0de; background-color: #fff; } .btn-warning { color: #fff; background-color: #f0ad4e; border-color: #eea236; } .btn-warning:focus, .btn-warning.focus { color: #fff; background-color: #ec971f; border-color: #985f0d; } .btn-warning:hover { color: #fff; background-color: #ec971f; border-color: #d58512; } .btn-warning:active, .btn-warning.active, .open > .dropdown-toggle.btn-warning { color: #fff; background-color: #ec971f; border-color: #d58512; } .btn-warning:active:hover, .btn-warning.active:hover, .open > .dropdown-toggle.btn-warning:hover, .btn-warning:active:focus, .btn-warning.active:focus, .open > .dropdown-toggle.btn-warning:focus, .btn-warning:active.focus, .btn-warning.active.focus, .open > .dropdown-toggle.btn-warning.focus { color: #fff; background-color: #d58512; border-color: #985f0d; } .btn-warning:active, .btn-warning.active, .open > .dropdown-toggle.btn-warning { background-image: none; } .btn-warning.disabled:hover, .btn-warning\[disabled\]:hover, fieldset\[disabled\] .btn-warning:hover, .btn-warning.disabled:focus, .btn-warning\[disabled\]:focus, fieldset\[disabled\] .btn-warning:focus, .btn-warning.disabled.focus, .btn-warning\[disabled\].focus, fieldset\[disabled\] .btn-warning.focus { background-color: #f0ad4e; border-color: #eea236; } .btn-warning .badge { color: #f0ad4e; background-color: #fff; } .btn-danger { color: #fff; background-color: #d9534f; border-color: #d43f3a; } .btn-danger:focus, .btn-danger.focus { color: #fff; background-color: #c9302c; border-color: #761c19; } .btn-danger:hover { color: #fff; background-color: #c9302c; border-color: #ac2925; } .btn-danger:active, .btn-danger.active, .open > .dropdown-toggle.btn-danger { color: #fff; background-color: #c9302c; border-color: #ac2925; } .btn-danger:active:hover, .btn-danger.active:hover, .open > .dropdown-toggle.btn-danger:hover, .btn-danger:active:focus, .btn-danger.active:focus, .open > .dropdown-toggle.btn-danger:focus, .btn-danger:active.focus, .btn-danger.active.focus, .open > .dropdown-toggle.btn-danger.focus { color: #fff; background-color: #ac2925; border-color: #761c19; } .btn-danger:active, .btn-danger.active, .open > .dropdown-toggle.btn-danger { background-image: none; } .btn-danger.disabled:hover, .btn-danger\[disabled\]:hover, fieldset\[disabled\] .btn-danger:hover, .btn-danger.disabled:focus, .btn-danger\[disabled\]:focus, fieldset\[disabled\] .btn-danger:focus, .btn-danger.disabled.focus, .btn-danger\[disabled\].focus, fieldset\[disabled\] .btn-danger.focus { background-color: #d9534f; border-color: #d43f3a; } .btn-danger .badge { color: #d9534f; background-color: #fff; } .btn-link { color: #337ab7; font-weight: normal; border-radius: 0; } .btn-link, .btn-link:active, .btn-link.active, .btn-link\[disabled\], fieldset\[disabled\] .btn-link { background-color: transparent; -webkit-box-shadow: none; box-shadow: none; } .btn-link, .btn-link:hover, .btn-link:focus, .btn-link:active { border-color: transparent; } .btn-link:hover, .btn-link:focus { color: #23527c; text-decoration: underline; background-color: transparent; } .btn-link\[disabled\]:hover, fieldset\[disabled\] .btn-link:hover, .btn-link\[disabled\]:focus, fieldset\[disabled\] .btn-link:focus { color: #777777; text-decoration: none; } .btn-lg, .btn-group-lg > .btn { padding: 10px 16px; font-size: 17px; line-height: 1.3333333; border-radius: 3px; } .btn-sm, .btn-group-sm > .btn { padding: 5px 10px; font-size: 12px; line-height: 1.5; border-radius: 1px; } .btn-xs, .btn-group-xs > .btn { padding: 1px 5px; font-size: 12px; line-height: 1.5; border-radius: 1px; } .btn-block { display: block; width: 100%; } .btn-block + .btn-block { margin-top: 5px; } input\[type="submit"\].btn-block, input\[type="reset"\].btn-block, input\[type="button"\].btn-block { width: 100%; } .fade { opacity: 0; -webkit-transition: opacity 0.15s linear; -o-transition: opacity 0.15s linear; transition: opacity 0.15s linear; } .fade.in { opacity: 1; } .collapse { display: none; } .collapse.in { display: block; } tr.collapse.in { display: table-row; } tbody.collapse.in { display: table-row-group; } .collapsing { position: relative; height: 0; overflow: hidden; -webkit-transition-property: height, visibility; transition-property: height, visibility; -webkit-transition-duration: 0.35s; transition-duration: 0.35s; -webkit-transition-timing-function: ease; transition-timing-function: ease; } .caret { display: inline-block; width: 0; height: 0; margin-left: 2px; vertical-align: middle; border-top: 4px dashed; border-top: 4px solid \\9; border-right: 4px solid transparent; border-left: 4px solid transparent; } .dropup, .dropdown { position: relative; } .dropdown-toggle:focus { outline: 0; } .dropdown-menu { position: absolute; top: 100%; left: 0; z-index: 1000; display: none; float: left; min-width: 160px; padding: 5px 0; margin: 2px 0 0; list-style: none; font-size: 13px; text-align: left; background-color: #fff; border: 1px solid #ccc; border: 1px solid rgba(0, 0, 0, 0.15); border-radius: 2px; -webkit-box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175); box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175); background-clip: padding-box; } .dropdown-menu.pull-right { right: 0; left: auto; } .dropdown-menu .divider { height: 1px; margin: 8px 0; overflow: hidden; background-color: #e5e5e5; } .dropdown-menu > li > a { display: block; padding: 3px 20px; clear: both; font-weight: normal; line-height: 1.42857143; color: #333333; white-space: nowrap; } .dropdown-menu > li > a:hover, .dropdown-menu > li > a:focus { text-decoration: none; color: #262626; background-color: #f5f5f5; } .dropdown-menu > .active > a, .dropdown-menu > .active > a:hover, .dropdown-menu > .active > a:focus { color: #fff; text-decoration: none; outline: 0; background-color: #337ab7; } .dropdown-menu > .disabled > a, .dropdown-menu > .disabled > a:hover, .dropdown-menu > .disabled > a:focus { color: #777777; } .dropdown-menu > .disabled > a:hover, .dropdown-menu > .disabled > a:focus { text-decoration: none; background-color: transparent; background-image: none; filter: progid:DXImageTransform.Microsoft.gradient(enabled = false); cursor: not-allowed; } .open > .dropdown-menu { display: block; } .open > a { outline: 0; } .dropdown-menu-right { left: auto; right: 0; } .dropdown-menu-left { left: 0; right: auto; } .dropdown-header { display: block; padding: 3px 20px; font-size: 12px; line-height: 1.42857143; color: #777777; white-space: nowrap; } .dropdown-backdrop { position: fixed; left: 0; right: 0; bottom: 0; top: 0; z-index: 990; } .pull-right > .dropdown-menu { right: 0; left: auto; } .dropup .caret, .navbar-fixed-bottom .dropdown .caret { border-top: 0; border-bottom: 4px dashed; border-bottom: 4px solid \\9; content: ""; } .dropup .dropdown-menu, .navbar-fixed-bottom .dropdown .dropdown-menu { top: auto; bottom: 100%; margin-bottom: 2px; } @media (min-width: 541px) { .navbar-right .dropdown-menu { left: auto; right: 0; } .navbar-right .dropdown-menu-left { left: 0; right: auto; } } .btn-group, .btn-group-vertical { position: relative; display: inline-block; vertical-align: middle; } .btn-group > .btn, .btn-group-vertical > .btn { position: relative; float: left; } .btn-group > .btn:hover, .btn-group-vertical > .btn:hover, .btn-group > .btn:focus, .btn-group-vertical > .btn:focus, .btn-group > .btn:active, .btn-group-vertical > .btn:active, .btn-group > .btn.active, .btn-group-vertical > .btn.active { z-index: 2; } .btn-group .btn + .btn, .btn-group .btn + .btn-group, .btn-group .btn-group + .btn, .btn-group .btn-group + .btn-group { margin-left: -1px; } .btn-toolbar { margin-left: -5px; } .btn-toolbar .btn, .btn-toolbar .btn-group, .btn-toolbar .input-group { float: left; } .btn-toolbar > .btn, .btn-toolbar > .btn-group, .btn-toolbar > .input-group { margin-left: 5px; } .btn-group > .btn:not(:first-child):not(:last-child):not(.dropdown-toggle) { border-radius: 0; } .btn-group > .btn:first-child { margin-left: 0; } .btn-group > .btn:first-child:not(:last-child):not(.dropdown-toggle) { border-bottom-right-radius: 0; border-top-right-radius: 0; } .btn-group > .btn:last-child:not(:first-child), .btn-group > .dropdown-toggle:not(:first-child) { border-bottom-left-radius: 0; border-top-left-radius: 0; } .btn-group > .btn-group { float: left; } .btn-group > .btn-group:not(:first-child):not(:last-child) > .btn { border-radius: 0; } .btn-group > .btn-group:first-child:not(:last-child) > .btn:last-child, .btn-group > .btn-group:first-child:not(:last-child) > .dropdown-toggle { border-bottom-right-radius: 0; border-top-right-radius: 0; } .btn-group > .btn-group:last-child:not(:first-child) > .btn:first-child { border-bottom-left-radius: 0; border-top-left-radius: 0; } .btn-group .dropdown-toggle:active, .btn-group.open .dropdown-toggle { outline: 0; } .btn-group > .btn + .dropdown-toggle { padding-left: 8px; padding-right: 8px; } .btn-group > .btn-lg + .dropdown-toggle { padding-left: 12px; padding-right: 12px; } .btn-group.open .dropdown-toggle { -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125); box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125); } .btn-group.open .dropdown-toggle.btn-link { -webkit-box-shadow: none; box-shadow: none; } .btn .caret { margin-left: 0; } .btn-lg .caret { border-width: 5px 5px 0; border-bottom-width: 0; } .dropup .btn-lg .caret { border-width: 0 5px 5px; } .btn-group-vertical > .btn, .btn-group-vertical > .btn-group, .btn-group-vertical > .btn-group > .btn { display: block; float: none; width: 100%; max-width: 100%; } .btn-group-vertical > .btn-group > .btn { float: none; } .btn-group-vertical > .btn + .btn, .btn-group-vertical > .btn + .btn-group, .btn-group-vertical > .btn-group + .btn, .btn-group-vertical > .btn-group + .btn-group { margin-top: -1px; margin-left: 0; } .btn-group-vertical > .btn:not(:first-child):not(:last-child) { border-radius: 0; } .btn-group-vertical > .btn:first-child:not(:last-child) { border-top-right-radius: 2px; border-top-left-radius: 2px; border-bottom-right-radius: 0; border-bottom-left-radius: 0; } .btn-group-vertical > .btn:last-child:not(:first-child) { border-top-right-radius: 0; border-top-left-radius: 0; border-bottom-right-radius: 2px; border-bottom-left-radius: 2px; } .btn-group-vertical > .btn-group:not(:first-child):not(:last-child) > .btn { border-radius: 0; } .btn-group-vertical > .btn-group:first-child:not(:last-child) > .btn:last-child, .btn-group-vertical > .btn-group:first-child:not(:last-child) > .dropdown-toggle { border-bottom-right-radius: 0; border-bottom-left-radius: 0; } .btn-group-vertical > .btn-group:last-child:not(:first-child) > .btn:first-child { border-top-right-radius: 0; border-top-left-radius: 0; } .btn-group-justified { display: table; width: 100%; table-layout: fixed; border-collapse: separate; } .btn-group-justified > .btn, .btn-group-justified > .btn-group { float: none; display: table-cell; width: 1%; } .btn-group-justified > .btn-group .btn { width: 100%; } .btn-group-justified > .btn-group .dropdown-menu { left: auto; } \[data-toggle="buttons"\] > .btn input\[type="radio"\], \[data-toggle="buttons"\] > .btn-group > .btn input\[type="radio"\], \[data-toggle="buttons"\] > .btn input\[type="checkbox"\], \[data-toggle="buttons"\] > .btn-group > .btn input\[type="checkbox"\] { position: absolute; clip: rect(0, 0, 0, 0); pointer-events: none; } .input-group { position: relative; display: table; border-collapse: separate; } .input-group\[class*="col-"\] { float: none; padding-left: 0; padding-right: 0; } .input-group .form-control { position: relative; z-index: 2; float: left; width: 100%; margin-bottom: 0; } .input-group .form-control:focus { z-index: 3; } .input-group-lg > .form-control, .input-group-lg > .input-group-addon, .input-group-lg > .input-group-btn > .btn { height: 45px; padding: 10px 16px; font-size: 17px; line-height: 1.3333333; border-radius: 3px; } select.input-group-lg > .form-control, select.input-group-lg > .input-group-addon, select.input-group-lg > .input-group-btn > .btn { height: 45px; line-height: 45px; } textarea.input-group-lg > .form-control, textarea.input-group-lg > .input-group-addon, textarea.input-group-lg > .input-group-btn > .btn, select\[multiple\].input-group-lg > .form-control, select\[multiple\].input-group-lg > .input-group-addon, select\[multiple\].input-group-lg > .input-group-btn > .btn { height: auto; } .input-group-sm > .form-control, .input-group-sm > .input-group-addon, .input-group-sm > .input-group-btn > .btn { height: 30px; padding: 5px 10px; font-size: 12px; line-height: 1.5; border-radius: 1px; } select.input-group-sm > .form-control, select.input-group-sm > .input-group-addon, select.input-group-sm > .input-group-btn > .btn { height: 30px; line-height: 30px; } textarea.input-group-sm > .form-control, textarea.input-group-sm > .input-group-addon, textarea.input-group-sm > .input-group-btn > .btn, select\[multiple\].input-group-sm > .form-control, select\[multiple\].input-group-sm > .input-group-addon, select\[multiple\].input-group-sm > .input-group-btn > .btn { height: auto; } .input-group-addon, .input-group-btn, .input-group .form-control { display: table-cell; } .input-group-addon:not(:first-child):not(:last-child), .input-group-btn:not(:first-child):not(:last-child), .input-group .form-control:not(:first-child):not(:last-child) { border-radius: 0; } .input-group-addon, .input-group-btn { width: 1%; white-space: nowrap; vertical-align: middle; } .input-group-addon { padding: 6px 12px; font-size: 13px; font-weight: normal; line-height: 1; color: #555555; text-align: center; background-color: #eeeeee; border: 1px solid #ccc; border-radius: 2px; } .input-group-addon.input-sm { padding: 5px 10px; font-size: 12px; border-radius: 1px; } .input-group-addon.input-lg { padding: 10px 16px; font-size: 17px; border-radius: 3px; } .input-group-addon input\[type="radio"\], .input-group-addon input\[type="checkbox"\] { margin-top: 0; } .input-group .form-control:first-child, .input-group-addon:first-child, .input-group-btn:first-child > .btn, .input-group-btn:first-child > .btn-group > .btn, .input-group-btn:first-child > .dropdown-toggle, .input-group-btn:last-child > .btn:not(:last-child):not(.dropdown-toggle), .input-group-btn:last-child > .btn-group:not(:last-child) > .btn { border-bottom-right-radius: 0; border-top-right-radius: 0; } .input-group-addon:first-child { border-right: 0; } .input-group .form-control:last-child, .input-group-addon:last-child, .input-group-btn:last-child > .btn, .input-group-btn:last-child > .btn-group > .btn, .input-group-btn:last-child > .dropdown-toggle, .input-group-btn:first-child > .btn:not(:first-child), .input-group-btn:first-child > .btn-group:not(:first-child) > .btn { border-bottom-left-radius: 0; border-top-left-radius: 0; } .input-group-addon:last-child { border-left: 0; } .input-group-btn { position: relative; font-size: 0; white-space: nowrap; } .input-group-btn > .btn { position: relative; } .input-group-btn > .btn + .btn { margin-left: -1px; } .input-group-btn > .btn:hover, .input-group-btn > .btn:focus, .input-group-btn > .btn:active { z-index: 2; } .input-group-btn:first-child > .btn, .input-group-btn:first-child > .btn-group { margin-right: -1px; } .input-group-btn:last-child > .btn, .input-group-btn:last-child > .btn-group { z-index: 2; margin-left: -1px; } .nav { margin-bottom: 0; padding-left: 0; list-style: none; } .nav > li { position: relative; display: block; } .nav > li > a { position: relative; display: block; padding: 10px 15px; } .nav > li > a:hover, .nav > li > a:focus { text-decoration: none; background-color: #eeeeee; } .nav > li.disabled > a { color: #777777; } .nav > li.disabled > a:hover, .nav > li.disabled > a:focus { color: #777777; text-decoration: none; background-color: transparent; cursor: not-allowed; } .nav .open > a, .nav .open > a:hover, .nav .open > a:focus { background-color: #eeeeee; border-color: #337ab7; } .nav .nav-divider { height: 1px; margin: 8px 0; overflow: hidden; background-color: #e5e5e5; } .nav > li > a > img { max-width: none; } .nav-tabs { border-bottom: 1px solid #ddd; } .nav-tabs > li { float: left; margin-bottom: -1px; } .nav-tabs > li > a { margin-right: 2px; line-height: 1.42857143; border: 1px solid transparent; border-radius: 2px 2px 0 0; } .nav-tabs > li > a:hover { border-color: #eeeeee #eeeeee #ddd; } .nav-tabs > li.active > a, .nav-tabs > li.active > a:hover, .nav-tabs > li.active > a:focus { color: #555555; background-color: #fff; border: 1px solid #ddd; border-bottom-color: transparent; cursor: default; } .nav-tabs.nav-justified { width: 100%; border-bottom: 0; } .nav-tabs.nav-justified > li { float: none; } .nav-tabs.nav-justified > li > a { text-align: center; margin-bottom: 5px; } .nav-tabs.nav-justified > .dropdown .dropdown-menu { top: auto; left: auto; } @media (min-width: 768px) { .nav-tabs.nav-justified > li { display: table-cell; width: 1%; } .nav-tabs.nav-justified > li > a { margin-bottom: 0; } } .nav-tabs.nav-justified > li > a { margin-right: 0; border-radius: 2px; } .nav-tabs.nav-justified > .active > a, .nav-tabs.nav-justified > .active > a:hover, .nav-tabs.nav-justified > .active > a:focus { border: 1px solid #ddd; } @media (min-width: 768px) { .nav-tabs.nav-justified > li > a { border-bottom: 1px solid #ddd; border-radius: 2px 2px 0 0; } .nav-tabs.nav-justified > .active > a, .nav-tabs.nav-justified > .active > a:hover, .nav-tabs.nav-justified > .active > a:focus { border-bottom-color: #fff; } } .nav-pills > li { float: left; } .nav-pills > li > a { border-radius: 2px; } .nav-pills > li + li { margin-left: 2px; } .nav-pills > li.active > a, .nav-pills > li.active > a:hover, .nav-pills > li.active > a:focus { color: #fff; background-color: #337ab7; } .nav-stacked > li { float: none; } .nav-stacked > li + li { margin-top: 2px; margin-left: 0; } .nav-justified { width: 100%; } .nav-justified > li { float: none; } .nav-justified > li > a { text-align: center; margin-bottom: 5px; } .nav-justified > .dropdown .dropdown-menu { top: auto; left: auto; } @media (min-width: 768px) { .nav-justified > li { display: table-cell; width: 1%; } .nav-justified > li > a { margin-bottom: 0; } } .nav-tabs-justified { border-bottom: 0; } .nav-tabs-justified > li > a { margin-right: 0; border-radius: 2px; } .nav-tabs-justified > .active > a, .nav-tabs-justified > .active > a:hover, .nav-tabs-justified > .active > a:focus { border: 1px solid #ddd; } @media (min-width: 768px) { .nav-tabs-justified > li > a { border-bottom: 1px solid #ddd; border-radius: 2px 2px 0 0; } .nav-tabs-justified > .active > a, .nav-tabs-justified > .active > a:hover, .nav-tabs-justified > .active > a:focus { border-bottom-color: #fff; } } .tab-content > .tab-pane { display: none; } .tab-content > .active { display: block; } .nav-tabs .dropdown-menu { margin-top: -1px; border-top-right-radius: 0; border-top-left-radius: 0; } .navbar { position: relative; min-height: 30px; margin-bottom: 18px; border: 1px solid transparent; } @media (min-width: 541px) { .navbar { border-radius: 2px; } } @media (min-width: 541px) { .navbar-header { float: left; } } .navbar-collapse { overflow-x: visible; padding-right: 0px; padding-left: 0px; border-top: 1px solid transparent; box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1); -webkit-overflow-scrolling: touch; } .navbar-collapse.in { overflow-y: auto; } @media (min-width: 541px) { .navbar-collapse { width: auto; border-top: 0; box-shadow: none; } .navbar-collapse.collapse { display: block !important; height: auto !important; padding-bottom: 0; overflow: visible !important; } .navbar-collapse.in { overflow-y: visible; } .navbar-fixed-top .navbar-collapse, .navbar-static-top .navbar-collapse, .navbar-fixed-bottom .navbar-collapse { padding-left: 0; padding-right: 0; } } .navbar-fixed-top .navbar-collapse, .navbar-fixed-bottom .navbar-collapse { max-height: 340px; } @media (max-device-width: 540px) and (orientation: landscape) { .navbar-fixed-top .navbar-collapse, .navbar-fixed-bottom .navbar-collapse { max-height: 200px; } } .container > .navbar-header, .container-fluid > .navbar-header, .container > .navbar-collapse, .container-fluid > .navbar-collapse { margin-right: 0px; margin-left: 0px; } @media (min-width: 541px) { .container > .navbar-header, .container-fluid > .navbar-header, .container > .navbar-collapse, .container-fluid > .navbar-collapse { margin-right: 0; margin-left: 0; } } .navbar-static-top { z-index: 1000; border-width: 0 0 1px; } @media (min-width: 541px) { .navbar-static-top { border-radius: 0; } } .navbar-fixed-top, .navbar-fixed-bottom { position: fixed; right: 0; left: 0; z-index: 1030; } @media (min-width: 541px) { .navbar-fixed-top, .navbar-fixed-bottom { border-radius: 0; } } .navbar-fixed-top { top: 0; border-width: 0 0 1px; } .navbar-fixed-bottom { bottom: 0; margin-bottom: 0; border-width: 1px 0 0; } .navbar-brand { float: left; padding: 6px 0px; font-size: 17px; line-height: 18px; height: 30px; } .navbar-brand:hover, .navbar-brand:focus { text-decoration: none; } .navbar-brand > img { display: block; } @media (min-width: 541px) { .navbar > .container .navbar-brand, .navbar > .container-fluid .navbar-brand { margin-left: 0px; } } .navbar-toggle { position: relative; float: right; margin-right: 0px; padding: 9px 10px; margin-top: -2px; margin-bottom: -2px; background-color: transparent; background-image: none; border: 1px solid transparent; border-radius: 2px; } .navbar-toggle:focus { outline: 0; } .navbar-toggle .icon-bar { display: block; width: 22px; height: 2px; border-radius: 1px; } .navbar-toggle .icon-bar + .icon-bar { margin-top: 4px; } @media (min-width: 541px) { .navbar-toggle { display: none; } } .navbar-nav { margin: 3px 0px; } .navbar-nav > li > a { padding-top: 10px; padding-bottom: 10px; line-height: 18px; } @media (max-width: 540px) { .navbar-nav .open .dropdown-menu { position: static; float: none; width: auto; margin-top: 0; background-color: transparent; border: 0; box-shadow: none; } .navbar-nav .open .dropdown-menu > li > a, .navbar-nav .open .dropdown-menu .dropdown-header { padding: 5px 15px 5px 25px; } .navbar-nav .open .dropdown-menu > li > a { line-height: 18px; } .navbar-nav .open .dropdown-menu > li > a:hover, .navbar-nav .open .dropdown-menu > li > a:focus { background-image: none; } } @media (min-width: 541px) { .navbar-nav { float: left; margin: 0; } .navbar-nav > li { float: left; } .navbar-nav > li > a { padding-top: 6px; padding-bottom: 6px; } } .navbar-form { margin-left: 0px; margin-right: 0px; padding: 10px 0px; border-top: 1px solid transparent; border-bottom: 1px solid transparent; -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1); box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1); margin-top: -1px; margin-bottom: -1px; } @media (min-width: 768px) { .navbar-form .form-group { display: inline-block; margin-bottom: 0; vertical-align: middle; } .navbar-form .form-control { display: inline-block; width: auto; vertical-align: middle; } .navbar-form .form-control-static { display: inline-block; } .navbar-form .input-group { display: inline-table; vertical-align: middle; } .navbar-form .input-group .input-group-addon, .navbar-form .input-group .input-group-btn, .navbar-form .input-group .form-control { width: auto; } .navbar-form .input-group > .form-control { width: 100%; } .navbar-form .control-label { margin-bottom: 0; vertical-align: middle; } .navbar-form .radio, .navbar-form .checkbox { display: inline-block; margin-top: 0; margin-bottom: 0; vertical-align: middle; } .navbar-form .radio label, .navbar-form .checkbox label { padding-left: 0; } .navbar-form .radio input\[type="radio"\], .navbar-form .checkbox input\[type="checkbox"\] { position: relative; margin-left: 0; } .navbar-form .has-feedback .form-control-feedback { top: 0; } } @media (max-width: 540px) { .navbar-form .form-group { margin-bottom: 5px; } .navbar-form .form-group:last-child { margin-bottom: 0; } } @media (min-width: 541px) { .navbar-form { width: auto; border: 0; margin-left: 0; margin-right: 0; padding-top: 0; padding-bottom: 0; -webkit-box-shadow: none; box-shadow: none; } } .navbar-nav > li > .dropdown-menu { margin-top: 0; border-top-right-radius: 0; border-top-left-radius: 0; } .navbar-fixed-bottom .navbar-nav > li > .dropdown-menu { margin-bottom: 0; border-top-right-radius: 2px; border-top-left-radius: 2px; border-bottom-right-radius: 0; border-bottom-left-radius: 0; } .navbar-btn { margin-top: -1px; margin-bottom: -1px; } .navbar-btn.btn-sm { margin-top: 0px; margin-bottom: 0px; } .navbar-btn.btn-xs { margin-top: 4px; margin-bottom: 4px; } .navbar-text { margin-top: 6px; margin-bottom: 6px; } @media (min-width: 541px) { .navbar-text { float: left; margin-left: 0px; margin-right: 0px; } } @media (min-width: 541px) { .navbar-left { float: left !important; float: left; } .navbar-right { float: right !important; float: right; margin-right: 0px; } .navbar-right ~ .navbar-right { margin-right: 0; } } .navbar-default { background-color: #f8f8f8; border-color: #e7e7e7; } .navbar-default .navbar-brand { color: #777; } .navbar-default .navbar-brand:hover, .navbar-default .navbar-brand:focus { color: #5e5e5e; background-color: transparent; } .navbar-default .navbar-text { color: #777; } .navbar-default .navbar-nav > li > a { color: #777; } .navbar-default .navbar-nav > li > a:hover, .navbar-default .navbar-nav > li > a:focus { color: #333; background-color: transparent; } .navbar-default .navbar-nav > .active > a, .navbar-default .navbar-nav > .active > a:hover, .navbar-default .navbar-nav > .active > a:focus { color: #555; background-color: #e7e7e7; } .navbar-default .navbar-nav > .disabled > a, .navbar-default .navbar-nav > .disabled > a:hover, .navbar-default .navbar-nav > .disabled > a:focus { color: #ccc; background-color: transparent; } .navbar-default .navbar-toggle { border-color: #ddd; } .navbar-default .navbar-toggle:hover, .navbar-default .navbar-toggle:focus { background-color: #ddd; } .navbar-default .navbar-toggle .icon-bar { background-color: #888; } .navbar-default .navbar-collapse, .navbar-default .navbar-form { border-color: #e7e7e7; } .navbar-default .navbar-nav > .open > a, .navbar-default .navbar-nav > .open > a:hover, .navbar-default .navbar-nav > .open > a:focus { background-color: #e7e7e7; color: #555; } @media (max-width: 540px) { .navbar-default .navbar-nav .open .dropdown-menu > li > a { color: #777; } .navbar-default .navbar-nav .open .dropdown-menu > li > a:hover, .navbar-default .navbar-nav .open .dropdown-menu > li > a:focus { color: #333; background-color: transparent; } .navbar-default .navbar-nav .open .dropdown-menu > .active > a, .navbar-default .navbar-nav .open .dropdown-menu > .active > a:hover, .navbar-default .navbar-nav .open .dropdown-menu > .active > a:focus { color: #555; background-color: #e7e7e7; } .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a, .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:hover, .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:focus { color: #ccc; background-color: transparent; } } .navbar-default .navbar-link { color: #777; } .navbar-default .navbar-link:hover { color: #333; } .navbar-default .btn-link { color: #777; } .navbar-default .btn-link:hover, .navbar-default .btn-link:focus { color: #333; } .navbar-default .btn-link\[disabled\]:hover, fieldset\[disabled\] .navbar-default .btn-link:hover, .navbar-default .btn-link\[disabled\]:focus, fieldset\[disabled\] .navbar-default .btn-link:focus { color: #ccc; } .navbar-inverse { background-color: #222; border-color: #080808; } .navbar-inverse .navbar-brand { color: #9d9d9d; } .navbar-inverse .navbar-brand:hover, .navbar-inverse .navbar-brand:focus { color: #fff; background-color: transparent; } .navbar-inverse .navbar-text { color: #9d9d9d; } .navbar-inverse .navbar-nav > li > a { color: #9d9d9d; } .navbar-inverse .navbar-nav > li > a:hover, .navbar-inverse .navbar-nav > li > a:focus { color: #fff; background-color: transparent; } .navbar-inverse .navbar-nav > .active > a, .navbar-inverse .navbar-nav > .active > a:hover, .navbar-inverse .navbar-nav > .active > a:focus { color: #fff; background-color: #080808; } .navbar-inverse .navbar-nav > .disabled > a, .navbar-inverse .navbar-nav > .disabled > a:hover, .navbar-inverse .navbar-nav > .disabled > a:focus { color: #444; background-color: transparent; } .navbar-inverse .navbar-toggle { border-color: #333; } .navbar-inverse .navbar-toggle:hover, .navbar-inverse .navbar-toggle:focus { background-color: #333; } .navbar-inverse .navbar-toggle .icon-bar { background-color: #fff; } .navbar-inverse .navbar-collapse, .navbar-inverse .navbar-form { border-color: #101010; } .navbar-inverse .navbar-nav > .open > a, .navbar-inverse .navbar-nav > .open > a:hover, .navbar-inverse .navbar-nav > .open > a:focus { background-color: #080808; color: #fff; } @media (max-width: 540px) { .navbar-inverse .navbar-nav .open .dropdown-menu > .dropdown-header { border-color: #080808; } .navbar-inverse .navbar-nav .open .dropdown-menu .divider { background-color: #080808; } .navbar-inverse .navbar-nav .open .dropdown-menu > li > a { color: #9d9d9d; } .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:hover, .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:focus { color: #fff; background-color: transparent; } .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a, .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:hover, .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:focus { color: #fff; background-color: #080808; } .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a, .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:hover, .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:focus { color: #444; background-color: transparent; } } .navbar-inverse .navbar-link { color: #9d9d9d; } .navbar-inverse .navbar-link:hover { color: #fff; } .navbar-inverse .btn-link { color: #9d9d9d; } .navbar-inverse .btn-link:hover, .navbar-inverse .btn-link:focus { color: #fff; } .navbar-inverse .btn-link\[disabled\]:hover, fieldset\[disabled\] .navbar-inverse .btn-link:hover, .navbar-inverse .btn-link\[disabled\]:focus, fieldset\[disabled\] .navbar-inverse .btn-link:focus { color: #444; } .breadcrumb { padding: 8px 15px; margin-bottom: 18px; list-style: none; background-color: #f5f5f5; border-radius: 2px; } .breadcrumb > li { display: inline-block; } .breadcrumb > li + li:before { content: "/\\00a0"; padding: 0 5px; color: #5e5e5e; } .breadcrumb > .active { color: #777777; } .pagination { display: inline-block; padding-left: 0; margin: 18px 0; border-radius: 2px; } .pagination > li { display: inline; } .pagination > li > a, .pagination > li > span { position: relative; float: left; padding: 6px 12px; line-height: 1.42857143; text-decoration: none; color: #337ab7; background-color: #fff; border: 1px solid #ddd; margin-left: -1px; } .pagination > li:first-child > a, .pagination > li:first-child > span { margin-left: 0; border-bottom-left-radius: 2px; border-top-left-radius: 2px; } .pagination > li:last-child > a, .pagination > li:last-child > span { border-bottom-right-radius: 2px; border-top-right-radius: 2px; } .pagination > li > a:hover, .pagination > li > span:hover, .pagination > li > a:focus, .pagination > li > span:focus { z-index: 2; color: #23527c; background-color: #eeeeee; border-color: #ddd; } .pagination > .active > a, .pagination > .active > span, .pagination > .active > a:hover, .pagination > .active > span:hover, .pagination > .active > a:focus, .pagination > .active > span:focus { z-index: 3; color: #fff; background-color: #337ab7; border-color: #337ab7; cursor: default; } .pagination > .disabled > span, .pagination > .disabled > span:hover, .pagination > .disabled > span:focus, .pagination > .disabled > a, .pagination > .disabled > a:hover, .pagination > .disabled > a:focus { color: #777777; background-color: #fff; border-color: #ddd; cursor: not-allowed; } .pagination-lg > li > a, .pagination-lg > li > span { padding: 10px 16px; font-size: 17px; line-height: 1.3333333; } .pagination-lg > li:first-child > a, .pagination-lg > li:first-child > span { border-bottom-left-radius: 3px; border-top-left-radius: 3px; } .pagination-lg > li:last-child > a, .pagination-lg > li:last-child > span { border-bottom-right-radius: 3px; border-top-right-radius: 3px; } .pagination-sm > li > a, .pagination-sm > li > span { padding: 5px 10px; font-size: 12px; line-height: 1.5; } .pagination-sm > li:first-child > a, .pagination-sm > li:first-child > span { border-bottom-left-radius: 1px; border-top-left-radius: 1px; } .pagination-sm > li:last-child > a, .pagination-sm > li:last-child > span { border-bottom-right-radius: 1px; border-top-right-radius: 1px; } .pager { padding-left: 0; margin: 18px 0; list-style: none; text-align: center; } .pager li { display: inline; } .pager li > a, .pager li > span { display: inline-block; padding: 5px 14px; background-color: #fff; border: 1px solid #ddd; border-radius: 15px; } .pager li > a:hover, .pager li > a:focus { text-decoration: none; background-color: #eeeeee; } .pager .next > a, .pager .next > span { float: right; } .pager .previous > a, .pager .previous > span { float: left; } .pager .disabled > a, .pager .disabled > a:hover, .pager .disabled > a:focus, .pager .disabled > span { color: #777777; background-color: #fff; cursor: not-allowed; } .label { display: inline; padding: .2em .6em .3em; font-size: 75%; font-weight: bold; line-height: 1; color: #fff; text-align: center; white-space: nowrap; vertical-align: baseline; border-radius: .25em; } a.label:hover, a.label:focus { color: #fff; text-decoration: none; cursor: pointer; } .label:empty { display: none; } .btn .label { position: relative; top: -1px; } .label-default { background-color: #777777; } .label-default\[href\]:hover, .label-default\[href\]:focus { background-color: #5e5e5e; } .label-primary { background-color: #337ab7; } .label-primary\[href\]:hover, .label-primary\[href\]:focus { background-color: #286090; } .label-success { background-color: #5cb85c; } .label-success\[href\]:hover, .label-success\[href\]:focus { background-color: #449d44; } .label-info { background-color: #5bc0de; } .label-info\[href\]:hover, .label-info\[href\]:focus { background-color: #31b0d5; } .label-warning { background-color: #f0ad4e; } .label-warning\[href\]:hover, .label-warning\[href\]:focus { background-color: #ec971f; } .label-danger { background-color: #d9534f; } .label-danger\[href\]:hover, .label-danger\[href\]:focus { background-color: #c9302c; } .badge { display: inline-block; min-width: 10px; padding: 3px 7px; font-size: 12px; font-weight: bold; color: #fff; line-height: 1; vertical-align: middle; white-space: nowrap; text-align: center; background-color: #777777; border-radius: 10px; } .badge:empty { display: none; } .btn .badge { position: relative; top: -1px; } .btn-xs .badge, .btn-group-xs > .btn .badge { top: 0; padding: 1px 5px; } a.badge:hover, a.badge:focus { color: #fff; text-decoration: none; cursor: pointer; } .list-group-item.active > .badge, .nav-pills > .active > a > .badge { color: #337ab7; background-color: #fff; } .list-group-item > .badge { float: right; } .list-group-item > .badge + .badge { margin-right: 5px; } .nav-pills > li > a > .badge { margin-left: 3px; } .jumbotron { padding-top: 30px; padding-bottom: 30px; margin-bottom: 30px; color: inherit; background-color: #eeeeee; } .jumbotron h1, .jumbotron .h1 { color: inherit; } .jumbotron p { margin-bottom: 15px; font-size: 20px; font-weight: 200; } .jumbotron > hr { border-top-color: #d5d5d5; } .container .jumbotron, .container-fluid .jumbotron { border-radius: 3px; padding-left: 0px; padding-right: 0px; } .jumbotron .container { max-width: 100%; } @media screen and (min-width: 768px) { .jumbotron { padding-top: 48px; padding-bottom: 48px; } .container .jumbotron, .container-fluid .jumbotron { padding-left: 60px; padding-right: 60px; } .jumbotron h1, .jumbotron .h1 { font-size: 59px; } } .thumbnail { display: block; padding: 4px; margin-bottom: 18px; line-height: 1.42857143; background-color: #fff; border: 1px solid #ddd; border-radius: 2px; -webkit-transition: border 0.2s ease-in-out; -o-transition: border 0.2s ease-in-out; transition: border 0.2s ease-in-out; } .thumbnail > img, .thumbnail a > img { margin-left: auto; margin-right: auto; } a.thumbnail:hover, a.thumbnail:focus, a.thumbnail.active { border-color: #337ab7; } .thumbnail .caption { padding: 9px; color: #000; } .alert { padding: 15px; margin-bottom: 18px; border: 1px solid transparent; border-radius: 2px; } .alert h4 { margin-top: 0; color: inherit; } .alert .alert-link { font-weight: bold; } .alert > p, .alert > ul { margin-bottom: 0; } .alert > p + p { margin-top: 5px; } .alert-dismissable, .alert-dismissible { padding-right: 35px; } .alert-dismissable .close, .alert-dismissible .close { position: relative; top: -2px; right: -21px; color: inherit; } .alert-success { background-color: #dff0d8; border-color: #d6e9c6; color: #3c763d; } .alert-success hr { border-top-color: #c9e2b3; } .alert-success .alert-link { color: #2b542c; } .alert-info { background-color: #d9edf7; border-color: #bce8f1; color: #31708f; } .alert-info hr { border-top-color: #a6e1ec; } .alert-info .alert-link { color: #245269; } .alert-warning { background-color: #fcf8e3; border-color: #faebcc; color: #8a6d3b; } .alert-warning hr { border-top-color: #f7e1b5; } .alert-warning .alert-link { color: #66512c; } .alert-danger { background-color: #f2dede; border-color: #ebccd1; color: #a94442; } .alert-danger hr { border-top-color: #e4b9c0; } .alert-danger .alert-link { color: #843534; } @-webkit-keyframes progress-bar-stripes { from { background-position: 40px 0; } to { background-position: 0 0; } } @keyframes progress-bar-stripes { from { background-position: 40px 0; } to { background-position: 0 0; } } .progress { overflow: hidden; height: 18px; margin-bottom: 18px; background-color: #f5f5f5; border-radius: 2px; -webkit-box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1); box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1); } .progress-bar { float: left; width: 0%; height: 100%; font-size: 12px; line-height: 18px; color: #fff; text-align: center; background-color: #337ab7; -webkit-box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15); box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15); -webkit-transition: width 0.6s ease; -o-transition: width 0.6s ease; transition: width 0.6s ease; } .progress-striped .progress-bar, .progress-bar-striped { background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); background-size: 40px 40px; } .progress.active .progress-bar, .progress-bar.active { -webkit-animation: progress-bar-stripes 2s linear infinite; -o-animation: progress-bar-stripes 2s linear infinite; animation: progress-bar-stripes 2s linear infinite; } .progress-bar-success { background-color: #5cb85c; } .progress-striped .progress-bar-success { background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); } .progress-bar-info { background-color: #5bc0de; } .progress-striped .progress-bar-info { background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); } .progress-bar-warning { background-color: #f0ad4e; } .progress-striped .progress-bar-warning { background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); } .progress-bar-danger { background-color: #d9534f; } .progress-striped .progress-bar-danger { background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); } .media { margin-top: 15px; } .media:first-child { margin-top: 0; } .media, .media-body { zoom: 1; overflow: hidden; } .media-body { width: 10000px; } .media-object { display: block; } .media-object.img-thumbnail { max-width: none; } .media-right, .media > .pull-right { padding-left: 10px; } .media-left, .media > .pull-left { padding-right: 10px; } .media-left, .media-right, .media-body { display: table-cell; vertical-align: top; } .media-middle { vertical-align: middle; } .media-bottom { vertical-align: bottom; } .media-heading { margin-top: 0; margin-bottom: 5px; } .media-list { padding-left: 0; list-style: none; } .list-group { margin-bottom: 20px; padding-left: 0; } .list-group-item { position: relative; display: block; padding: 10px 15px; margin-bottom: -1px; background-color: #fff; border: 1px solid #ddd; } .list-group-item:first-child { border-top-right-radius: 2px; border-top-left-radius: 2px; } .list-group-item:last-child { margin-bottom: 0; border-bottom-right-radius: 2px; border-bottom-left-radius: 2px; } a.list-group-item, button.list-group-item { color: #555; } a.list-group-item .list-group-item-heading, button.list-group-item .list-group-item-heading { color: #333; } a.list-group-item:hover, button.list-group-item:hover, a.list-group-item:focus, button.list-group-item:focus { text-decoration: none; color: #555; background-color: #f5f5f5; } button.list-group-item { width: 100%; text-align: left; } .list-group-item.disabled, .list-group-item.disabled:hover, .list-group-item.disabled:focus { background-color: #eeeeee; color: #777777; cursor: not-allowed; } .list-group-item.disabled .list-group-item-heading, .list-group-item.disabled:hover .list-group-item-heading, .list-group-item.disabled:focus .list-group-item-heading { color: inherit; } .list-group-item.disabled .list-group-item-text, .list-group-item.disabled:hover .list-group-item-text, .list-group-item.disabled:focus .list-group-item-text { color: #777777; } .list-group-item.active, .list-group-item.active:hover, .list-group-item.active:focus { z-index: 2; color: #fff; background-color: #337ab7; border-color: #337ab7; } .list-group-item.active .list-group-item-heading, .list-group-item.active:hover .list-group-item-heading, .list-group-item.active:focus .list-group-item-heading, .list-group-item.active .list-group-item-heading > small, .list-group-item.active:hover .list-group-item-heading > small, .list-group-item.active:focus .list-group-item-heading > small, .list-group-item.active .list-group-item-heading > .small, .list-group-item.active:hover .list-group-item-heading > .small, .list-group-item.active:focus .list-group-item-heading > .small { color: inherit; } .list-group-item.active .list-group-item-text, .list-group-item.active:hover .list-group-item-text, .list-group-item.active:focus .list-group-item-text { color: #c7ddef; } .list-group-item-success { color: #3c763d; background-color: #dff0d8; } a.list-group-item-success, button.list-group-item-success { color: #3c763d; } a.list-group-item-success .list-group-item-heading, button.list-group-item-success .list-group-item-heading { color: inherit; } a.list-group-item-success:hover, button.list-group-item-success:hover, a.list-group-item-success:focus, button.list-group-item-success:focus { color: #3c763d; background-color: #d0e9c6; } a.list-group-item-success.active, button.list-group-item-success.active, a.list-group-item-success.active:hover, button.list-group-item-success.active:hover, a.list-group-item-success.active:focus, button.list-group-item-success.active:focus { color: #fff; background-color: #3c763d; border-color: #3c763d; } .list-group-item-info { color: #31708f; background-color: #d9edf7; } a.list-group-item-info, button.list-group-item-info { color: #31708f; } a.list-group-item-info .list-group-item-heading, button.list-group-item-info .list-group-item-heading { color: inherit; } a.list-group-item-info:hover, button.list-group-item-info:hover, a.list-group-item-info:focus, button.list-group-item-info:focus { color: #31708f; background-color: #c4e3f3; } a.list-group-item-info.active, button.list-group-item-info.active, a.list-group-item-info.active:hover, button.list-group-item-info.active:hover, a.list-group-item-info.active:focus, button.list-group-item-info.active:focus { color: #fff; background-color: #31708f; border-color: #31708f; } .list-group-item-warning { color: #8a6d3b; background-color: #fcf8e3; } a.list-group-item-warning, button.list-group-item-warning { color: #8a6d3b; } a.list-group-item-warning .list-group-item-heading, button.list-group-item-warning .list-group-item-heading { color: inherit; } a.list-group-item-warning:hover, button.list-group-item-warning:hover, a.list-group-item-warning:focus, button.list-group-item-warning:focus { color: #8a6d3b; background-color: #faf2cc; } a.list-group-item-warning.active, button.list-group-item-warning.active, a.list-group-item-warning.active:hover, button.list-group-item-warning.active:hover, a.list-group-item-warning.active:focus, button.list-group-item-warning.active:focus { color: #fff; background-color: #8a6d3b; border-color: #8a6d3b; } .list-group-item-danger { color: #a94442; background-color: #f2dede; } a.list-group-item-danger, button.list-group-item-danger { color: #a94442; } a.list-group-item-danger .list-group-item-heading, button.list-group-item-danger .list-group-item-heading { color: inherit; } a.list-group-item-danger:hover, button.list-group-item-danger:hover, a.list-group-item-danger:focus, button.list-group-item-danger:focus { color: #a94442; background-color: #ebcccc; } a.list-group-item-danger.active, button.list-group-item-danger.active, a.list-group-item-danger.active:hover, button.list-group-item-danger.active:hover, a.list-group-item-danger.active:focus, button.list-group-item-danger.active:focus { color: #fff; background-color: #a94442; border-color: #a94442; } .list-group-item-heading { margin-top: 0; margin-bottom: 5px; } .list-group-item-text { margin-bottom: 0; line-height: 1.3; } .panel { margin-bottom: 18px; background-color: #fff; border: 1px solid transparent; border-radius: 2px; -webkit-box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05); box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05); } .panel-body { padding: 15px; } .panel-heading { padding: 10px 15px; border-bottom: 1px solid transparent; border-top-right-radius: 1px; border-top-left-radius: 1px; } .panel-heading > .dropdown .dropdown-toggle { color: inherit; } .panel-title { margin-top: 0; margin-bottom: 0; font-size: 15px; color: inherit; } .panel-title > a, .panel-title > small, .panel-title > .small, .panel-title > small > a, .panel-title > .small > a { color: inherit; } .panel-footer { padding: 10px 15px; background-color: #f5f5f5; border-top: 1px solid #ddd; border-bottom-right-radius: 1px; border-bottom-left-radius: 1px; } .panel > .list-group, .panel > .panel-collapse > .list-group { margin-bottom: 0; } .panel > .list-group .list-group-item, .panel > .panel-collapse > .list-group .list-group-item { border-width: 1px 0; border-radius: 0; } .panel > .list-group:first-child .list-group-item:first-child, .panel > .panel-collapse > .list-group:first-child .list-group-item:first-child { border-top: 0; border-top-right-radius: 1px; border-top-left-radius: 1px; } .panel > .list-group:last-child .list-group-item:last-child, .panel > .panel-collapse > .list-group:last-child .list-group-item:last-child { border-bottom: 0; border-bottom-right-radius: 1px; border-bottom-left-radius: 1px; } .panel > .panel-heading + .panel-collapse > .list-group .list-group-item:first-child { border-top-right-radius: 0; border-top-left-radius: 0; } .panel-heading + .list-group .list-group-item:first-child { border-top-width: 0; } .list-group + .panel-footer { border-top-width: 0; } .panel > .table, .panel > .table-responsive > .table, .panel > .panel-collapse > .table { margin-bottom: 0; } .panel > .table caption, .panel > .table-responsive > .table caption, .panel > .panel-collapse > .table caption { padding-left: 15px; padding-right: 15px; } .panel > .table:first-child, .panel > .table-responsive:first-child > .table:first-child { border-top-right-radius: 1px; border-top-left-radius: 1px; } .panel > .table:first-child > thead:first-child > tr:first-child, .panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child, .panel > .table:first-child > tbody:first-child > tr:first-child, .panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child { border-top-left-radius: 1px; border-top-right-radius: 1px; } .panel > .table:first-child > thead:first-child > tr:first-child td:first-child, .panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:first-child, .panel > .table:first-child > tbody:first-child > tr:first-child td:first-child, .panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:first-child, .panel > .table:first-child > thead:first-child > tr:first-child th:first-child, .panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:first-child, .panel > .table:first-child > tbody:first-child > tr:first-child th:first-child, .panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:first-child { border-top-left-radius: 1px; } .panel > .table:first-child > thead:first-child > tr:first-child td:last-child, .panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:last-child, .panel > .table:first-child > tbody:first-child > tr:first-child td:last-child, .panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:last-child, .panel > .table:first-child > thead:first-child > tr:first-child th:last-child, .panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:last-child, .panel > .table:first-child > tbody:first-child > tr:first-child th:last-child, .panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:last-child { border-top-right-radius: 1px; } .panel > .table:last-child, .panel > .table-responsive:last-child > .table:last-child { border-bottom-right-radius: 1px; border-bottom-left-radius: 1px; } .panel > .table:last-child > tbody:last-child > tr:last-child, .panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child, .panel > .table:last-child > tfoot:last-child > tr:last-child, .panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child { border-bottom-left-radius: 1px; border-bottom-right-radius: 1px; } .panel > .table:last-child > tbody:last-child > tr:last-child td:first-child, .panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:first-child, .panel > .table:last-child > tfoot:last-child > tr:last-child td:first-child, .panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:first-child, .panel > .table:last-child > tbody:last-child > tr:last-child th:first-child, .panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:first-child, .panel > .table:last-child > tfoot:last-child > tr:last-child th:first-child, .panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:first-child { border-bottom-left-radius: 1px; } .panel > .table:last-child > tbody:last-child > tr:last-child td:last-child, .panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:last-child, .panel > .table:last-child > tfoot:last-child > tr:last-child td:last-child, .panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:last-child, .panel > .table:last-child > tbody:last-child > tr:last-child th:last-child, .panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:last-child, .panel > .table:last-child > tfoot:last-child > tr:last-child th:last-child, .panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:last-child { border-bottom-right-radius: 1px; } .panel > .panel-body + .table, .panel > .panel-body + .table-responsive, .panel > .table + .panel-body, .panel > .table-responsive + .panel-body { border-top: 1px solid #ddd; } .panel > .table > tbody:first-child > tr:first-child th, .panel > .table > tbody:first-child > tr:first-child td { border-top: 0; } .panel > .table-bordered, .panel > .table-responsive > .table-bordered { border: 0; } .panel > .table-bordered > thead > tr > th:first-child, .panel > .table-responsive > .table-bordered > thead > tr > th:first-child, .panel > .table-bordered > tbody > tr > th:first-child, .panel > .table-responsive > .table-bordered > tbody > tr > th:first-child, .panel > .table-bordered > tfoot > tr > th:first-child, .panel > .table-responsive > .table-bordered > tfoot > tr > th:first-child, .panel > .table-bordered > thead > tr > td:first-child, .panel > .table-responsive > .table-bordered > thead > tr > td:first-child, .panel > .table-bordered > tbody > tr > td:first-child, .panel > .table-responsive > .table-bordered > tbody > tr > td:first-child, .panel > .table-bordered > tfoot > tr > td:first-child, .panel > .table-responsive > .table-bordered > tfoot > tr > td:first-child { border-left: 0; } .panel > .table-bordered > thead > tr > th:last-child, .panel > .table-responsive > .table-bordered > thead > tr > th:last-child, .panel > .table-bordered > tbody > tr > th:last-child, .panel > .table-responsive > .table-bordered > tbody > tr > th:last-child, .panel > .table-bordered > tfoot > tr > th:last-child, .panel > .table-responsive > .table-bordered > tfoot > tr > th:last-child, .panel > .table-bordered > thead > tr > td:last-child, .panel > .table-responsive > .table-bordered > thead > tr > td:last-child, .panel > .table-bordered > tbody > tr > td:last-child, .panel > .table-responsive > .table-bordered > tbody > tr > td:last-child, .panel > .table-bordered > tfoot > tr > td:last-child, .panel > .table-responsive > .table-bordered > tfoot > tr > td:last-child { border-right: 0; } .panel > .table-bordered > thead > tr:first-child > td, .panel > .table-responsive > .table-bordered > thead > tr:first-child > td, .panel > .table-bordered > tbody > tr:first-child > td, .panel > .table-responsive > .table-bordered > tbody > tr:first-child > td, .panel > .table-bordered > thead > tr:first-child > th, .panel > .table-responsive > .table-bordered > thead > tr:first-child > th, .panel > .table-bordered > tbody > tr:first-child > th, .panel > .table-responsive > .table-bordered > tbody > tr:first-child > th { border-bottom: 0; } .panel > .table-bordered > tbody > tr:last-child > td, .panel > .table-responsive > .table-bordered > tbody > tr:last-child > td, .panel > .table-bordered > tfoot > tr:last-child > td, .panel > .table-responsive > .table-bordered > tfoot > tr:last-child > td, .panel > .table-bordered > tbody > tr:last-child > th, .panel > .table-responsive > .table-bordered > tbody > tr:last-child > th, .panel > .table-bordered > tfoot > tr:last-child > th, .panel > .table-responsive > .table-bordered > tfoot > tr:last-child > th { border-bottom: 0; } .panel > .table-responsive { border: 0; margin-bottom: 0; } .panel-group { margin-bottom: 18px; } .panel-group .panel { margin-bottom: 0; border-radius: 2px; } .panel-group .panel + .panel { margin-top: 5px; } .panel-group .panel-heading { border-bottom: 0; } .panel-group .panel-heading + .panel-collapse > .panel-body, .panel-group .panel-heading + .panel-collapse > .list-group { border-top: 1px solid #ddd; } .panel-group .panel-footer { border-top: 0; } .panel-group .panel-footer + .panel-collapse .panel-body { border-bottom: 1px solid #ddd; } .panel-default { border-color: #ddd; } .panel-default > .panel-heading { color: #333333; background-color: #f5f5f5; border-color: #ddd; } .panel-default > .panel-heading + .panel-collapse > .panel-body { border-top-color: #ddd; } .panel-default > .panel-heading .badge { color: #f5f5f5; background-color: #333333; } .panel-default > .panel-footer + .panel-collapse > .panel-body { border-bottom-color: #ddd; } .panel-primary { border-color: #337ab7; } .panel-primary > .panel-heading { color: #fff; background-color: #337ab7; border-color: #337ab7; } .panel-primary > .panel-heading + .panel-collapse > .panel-body { border-top-color: #337ab7; } .panel-primary > .panel-heading .badge { color: #337ab7; background-color: #fff; } .panel-primary > .panel-footer + .panel-collapse > .panel-body { border-bottom-color: #337ab7; } .panel-success { border-color: #d6e9c6; } .panel-success > .panel-heading { color: #3c763d; background-color: #dff0d8; border-color: #d6e9c6; } .panel-success > .panel-heading + .panel-collapse > .panel-body { border-top-color: #d6e9c6; } .panel-success > .panel-heading .badge { color: #dff0d8; background-color: #3c763d; } .panel-success > .panel-footer + .panel-collapse > .panel-body { border-bottom-color: #d6e9c6; } .panel-info { border-color: #bce8f1; } .panel-info > .panel-heading { color: #31708f; background-color: #d9edf7; border-color: #bce8f1; } .panel-info > .panel-heading + .panel-collapse > .panel-body { border-top-color: #bce8f1; } .panel-info > .panel-heading .badge { color: #d9edf7; background-color: #31708f; } .panel-info > .panel-footer + .panel-collapse > .panel-body { border-bottom-color: #bce8f1; } .panel-warning { border-color: #faebcc; } .panel-warning > .panel-heading { color: #8a6d3b; background-color: #fcf8e3; border-color: #faebcc; } .panel-warning > .panel-heading + .panel-collapse > .panel-body { border-top-color: #faebcc; } .panel-warning > .panel-heading .badge { color: #fcf8e3; background-color: #8a6d3b; } .panel-warning > .panel-footer + .panel-collapse > .panel-body { border-bottom-color: #faebcc; } .panel-danger { border-color: #ebccd1; } .panel-danger > .panel-heading { color: #a94442; background-color: #f2dede; border-color: #ebccd1; } .panel-danger > .panel-heading + .panel-collapse > .panel-body { border-top-color: #ebccd1; } .panel-danger > .panel-heading .badge { color: #f2dede; background-color: #a94442; } .panel-danger > .panel-footer + .panel-collapse > .panel-body { border-bottom-color: #ebccd1; } .embed-responsive { position: relative; display: block; height: 0; padding: 0; overflow: hidden; } .embed-responsive .embed-responsive-item, .embed-responsive iframe, .embed-responsive embed, .embed-responsive object, .embed-responsive video { position: absolute; top: 0; left: 0; bottom: 0; height: 100%; width: 100%; border: 0; } .embed-responsive-16by9 { padding-bottom: 56.25%; } .embed-responsive-4by3 { padding-bottom: 75%; } .well { min-height: 20px; padding: 19px; margin-bottom: 20px; background-color: #f5f5f5; border: 1px solid #e3e3e3; border-radius: 2px; -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05); box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05); } .well blockquote { border-color: #ddd; border-color: rgba(0, 0, 0, 0.15); } .well-lg { padding: 24px; border-radius: 3px; } .well-sm { padding: 9px; border-radius: 1px; } .close { float: right; font-size: 19.5px; font-weight: bold; line-height: 1; color: #000; text-shadow: 0 1px 0 #fff; opacity: 0.2; filter: alpha(opacity=20); } .close:hover, .close:focus { color: #000; text-decoration: none; cursor: pointer; opacity: 0.5; filter: alpha(opacity=50); } button.close { padding: 0; cursor: pointer; background: transparent; border: 0; -webkit-appearance: none; } .modal-open { overflow: hidden; } .modal { display: none; overflow: hidden; position: fixed; top: 0; right: 0; bottom: 0; left: 0; z-index: 1050; -webkit-overflow-scrolling: touch; outline: 0; } .modal.fade .modal-dialog { -webkit-transform: translate(0, -25%); -ms-transform: translate(0, -25%); -o-transform: translate(0, -25%); transform: translate(0, -25%); -webkit-transition: -webkit-transform 0.3s ease-out; -moz-transition: -moz-transform 0.3s ease-out; -o-transition: -o-transform 0.3s ease-out; transition: transform 0.3s ease-out; } .modal.in .modal-dialog { -webkit-transform: translate(0, 0); -ms-transform: translate(0, 0); -o-transform: translate(0, 0); transform: translate(0, 0); } .modal-open .modal { overflow-x: hidden; overflow-y: auto; } .modal-dialog { position: relative; width: auto; margin: 10px; } .modal-content { position: relative; background-color: #fff; border: 1px solid #999; border: 1px solid rgba(0, 0, 0, 0.2); border-radius: 3px; -webkit-box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5); box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5); background-clip: padding-box; outline: 0; } .modal-backdrop { position: fixed; top: 0; right: 0; bottom: 0; left: 0; z-index: 1040; background-color: #000; } .modal-backdrop.fade { opacity: 0; filter: alpha(opacity=0); } .modal-backdrop.in { opacity: 0.5; filter: alpha(opacity=50); } .modal-header { padding: 15px; border-bottom: 1px solid #e5e5e5; } .modal-header .close { margin-top: -2px; } .modal-title { margin: 0; line-height: 1.42857143; } .modal-body { position: relative; padding: 15px; } .modal-footer { padding: 15px; text-align: right; border-top: 1px solid #e5e5e5; } .modal-footer .btn + .btn { margin-left: 5px; margin-bottom: 0; } .modal-footer .btn-group .btn + .btn { margin-left: -1px; } .modal-footer .btn-block + .btn-block { margin-left: 0; } .modal-scrollbar-measure { position: absolute; top: -9999px; width: 50px; height: 50px; overflow: scroll; } @media (min-width: 768px) { .modal-dialog { width: 600px; margin: 30px auto; } .modal-content { -webkit-box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5); box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5); } .modal-sm { width: 300px; } } @media (min-width: 992px) { .modal-lg { width: 900px; } } .tooltip { position: absolute; z-index: 1070; display: block; font-family: "Helvetica Neue", Helvetica, Arial, sans-serif; font-style: normal; font-weight: normal; letter-spacing: normal; line-break: auto; line-height: 1.42857143; text-align: left; text-align: start; text-decoration: none; text-shadow: none; text-transform: none; white-space: normal; word-break: normal; word-spacing: normal; word-wrap: normal; font-size: 12px; opacity: 0; filter: alpha(opacity=0); } .tooltip.in { opacity: 0.9; filter: alpha(opacity=90); } .tooltip.top { margin-top: -3px; padding: 5px 0; } .tooltip.right { margin-left: 3px; padding: 0 5px; } .tooltip.bottom { margin-top: 3px; padding: 5px 0; } .tooltip.left { margin-left: -3px; padding: 0 5px; } .tooltip-inner { max-width: 200px; padding: 3px 8px; color: #fff; text-align: center; background-color: #000; border-radius: 2px; } .tooltip-arrow { position: absolute; width: 0; height: 0; border-color: transparent; border-style: solid; } .tooltip.top .tooltip-arrow { bottom: 0; left: 50%; margin-left: -5px; border-width: 5px 5px 0; border-top-color: #000; } .tooltip.top-left .tooltip-arrow { bottom: 0; right: 5px; margin-bottom: -5px; border-width: 5px 5px 0; border-top-color: #000; } .tooltip.top-right .tooltip-arrow { bottom: 0; left: 5px; margin-bottom: -5px; border-width: 5px 5px 0; border-top-color: #000; } .tooltip.right .tooltip-arrow { top: 50%; left: 0; margin-top: -5px; border-width: 5px 5px 5px 0; border-right-color: #000; } .tooltip.left .tooltip-arrow { top: 50%; right: 0; margin-top: -5px; border-width: 5px 0 5px 5px; border-left-color: #000; } .tooltip.bottom .tooltip-arrow { top: 0; left: 50%; margin-left: -5px; border-width: 0 5px 5px; border-bottom-color: #000; } .tooltip.bottom-left .tooltip-arrow { top: 0; right: 5px; margin-top: -5px; border-width: 0 5px 5px; border-bottom-color: #000; } .tooltip.bottom-right .tooltip-arrow { top: 0; left: 5px; margin-top: -5px; border-width: 0 5px 5px; border-bottom-color: #000; } .popover { position: absolute; top: 0; left: 0; z-index: 1060; display: none; max-width: 276px; padding: 1px; font-family: "Helvetica Neue", Helvetica, Arial, sans-serif; font-style: normal; font-weight: normal; letter-spacing: normal; line-break: auto; line-height: 1.42857143; text-align: left; text-align: start; text-decoration: none; text-shadow: none; text-transform: none; white-space: normal; word-break: normal; word-spacing: normal; word-wrap: normal; font-size: 13px; background-color: #fff; background-clip: padding-box; border: 1px solid #ccc; border: 1px solid rgba(0, 0, 0, 0.2); border-radius: 3px; -webkit-box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2); box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2); } .popover.top { margin-top: -10px; } .popover.right { margin-left: 10px; } .popover.bottom { margin-top: 10px; } .popover.left { margin-left: -10px; } .popover-title { margin: 0; padding: 8px 14px; font-size: 13px; background-color: #f7f7f7; border-bottom: 1px solid #ebebeb; border-radius: 2px 2px 0 0; } .popover-content { padding: 9px 14px; } .popover > .arrow, .popover > .arrow:after { position: absolute; display: block; width: 0; height: 0; border-color: transparent; border-style: solid; } .popover > .arrow { border-width: 11px; } .popover > .arrow:after { border-width: 10px; content: ""; } .popover.top > .arrow { left: 50%; margin-left: -11px; border-bottom-width: 0; border-top-color: #999999; border-top-color: rgba(0, 0, 0, 0.25); bottom: -11px; } .popover.top > .arrow:after { content: " "; bottom: 1px; margin-left: -10px; border-bottom-width: 0; border-top-color: #fff; } .popover.right > .arrow { top: 50%; left: -11px; margin-top: -11px; border-left-width: 0; border-right-color: #999999; border-right-color: rgba(0, 0, 0, 0.25); } .popover.right > .arrow:after { content: " "; left: 1px; bottom: -10px; border-left-width: 0; border-right-color: #fff; } .popover.bottom > .arrow { left: 50%; margin-left: -11px; border-top-width: 0; border-bottom-color: #999999; border-bottom-color: rgba(0, 0, 0, 0.25); top: -11px; } .popover.bottom > .arrow:after { content: " "; top: 1px; margin-left: -10px; border-top-width: 0; border-bottom-color: #fff; } .popover.left > .arrow { top: 50%; right: -11px; margin-top: -11px; border-right-width: 0; border-left-color: #999999; border-left-color: rgba(0, 0, 0, 0.25); } .popover.left > .arrow:after { content: " "; right: 1px; border-right-width: 0; border-left-color: #fff; bottom: -10px; } .carousel { position: relative; } .carousel-inner { position: relative; overflow: hidden; width: 100%; } .carousel-inner > .item { display: none; position: relative; -webkit-transition: 0.6s ease-in-out left; -o-transition: 0.6s ease-in-out left; transition: 0.6s ease-in-out left; } .carousel-inner > .item > img, .carousel-inner > .item > a > img { line-height: 1; } @media all and (transform-3d), (-webkit-transform-3d) { .carousel-inner > .item { -webkit-transition: -webkit-transform 0.6s ease-in-out; -moz-transition: -moz-transform 0.6s ease-in-out; -o-transition: -o-transform 0.6s ease-in-out; transition: transform 0.6s ease-in-out; -webkit-backface-visibility: hidden; -moz-backface-visibility: hidden; backface-visibility: hidden; -webkit-perspective: 1000px; -moz-perspective: 1000px; perspective: 1000px; } .carousel-inner > .item.next, .carousel-inner > .item.active.right { -webkit-transform: translate3d(100%, 0, 0); transform: translate3d(100%, 0, 0); left: 0; } .carousel-inner > .item.prev, .carousel-inner > .item.active.left { -webkit-transform: translate3d(-100%, 0, 0); transform: translate3d(-100%, 0, 0); left: 0; } .carousel-inner > .item.next.left, .carousel-inner > .item.prev.right, .carousel-inner > .item.active { -webkit-transform: translate3d(0, 0, 0); transform: translate3d(0, 0, 0); left: 0; } } .carousel-inner > .active, .carousel-inner > .next, .carousel-inner > .prev { display: block; } .carousel-inner > .active { left: 0; } .carousel-inner > .next, .carousel-inner > .prev { position: absolute; top: 0; width: 100%; } .carousel-inner > .next { left: 100%; } .carousel-inner > .prev { left: -100%; } .carousel-inner > .next.left, .carousel-inner > .prev.right { left: 0; } .carousel-inner > .active.left { left: -100%; } .carousel-inner > .active.right { left: 100%; } .carousel-control { position: absolute; top: 0; left: 0; bottom: 0; width: 15%; opacity: 0.5; filter: alpha(opacity=50); font-size: 20px; color: #fff; text-align: center; text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6); background-color: rgba(0, 0, 0, 0); } .carousel-control.left { background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%); background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%); background-image: linear-gradient(to right, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%); background-repeat: repeat-x; filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#80000000', endColorstr='#00000000', GradientType=1); } .carousel-control.right { left: auto; right: 0; background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%); background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%); background-image: linear-gradient(to right, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%); background-repeat: repeat-x; filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#00000000', endColorstr='#80000000', GradientType=1); } .carousel-control:hover, .carousel-control:focus { outline: 0; color: #fff; text-decoration: none; opacity: 0.9; filter: alpha(opacity=90); } .carousel-control .icon-prev, .carousel-control .icon-next, .carousel-control .glyphicon-chevron-left, .carousel-control .glyphicon-chevron-right { position: absolute; top: 50%; margin-top: -10px; z-index: 5; display: inline-block; } .carousel-control .icon-prev, .carousel-control .glyphicon-chevron-left { left: 50%; margin-left: -10px; } .carousel-control .icon-next, .carousel-control .glyphicon-chevron-right { right: 50%; margin-right: -10px; } .carousel-control .icon-prev, .carousel-control .icon-next { width: 20px; height: 20px; line-height: 1; font-family: serif; } .carousel-control .icon-prev:before { content: '\\2039'; } .carousel-control .icon-next:before { content: '\\203a'; } .carousel-indicators { position: absolute; bottom: 10px; left: 50%; z-index: 15; width: 60%; margin-left: -30%; padding-left: 0; list-style: none; text-align: center; } .carousel-indicators li { display: inline-block; width: 10px; height: 10px; margin: 1px; text-indent: -999px; border: 1px solid #fff; border-radius: 10px; cursor: pointer; background-color: #000 \\9; background-color: rgba(0, 0, 0, 0); } .carousel-indicators .active { margin: 0; width: 12px; height: 12px; background-color: #fff; } .carousel-caption { position: absolute; left: 15%; right: 15%; bottom: 20px; z-index: 10; padding-top: 20px; padding-bottom: 20px; color: #fff; text-align: center; text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6); } .carousel-caption .btn { text-shadow: none; } @media screen and (min-width: 768px) { .carousel-control .glyphicon-chevron-left, .carousel-control .glyphicon-chevron-right, .carousel-control .icon-prev, .carousel-control .icon-next { width: 30px; height: 30px; margin-top: -10px; font-size: 30px; } .carousel-control .glyphicon-chevron-left, .carousel-control .icon-prev { margin-left: -10px; } .carousel-control .glyphicon-chevron-right, .carousel-control .icon-next { margin-right: -10px; } .carousel-caption { left: 20%; right: 20%; padding-bottom: 30px; } .carousel-indicators { bottom: 20px; } } .clearfix:before, .clearfix:after, .dl-horizontal dd:before, .dl-horizontal dd:after, .container:before, .container:after, .container-fluid:before, .container-fluid:after, .row:before, .row:after, .form-horizontal .form-group:before, .form-horizontal .form-group:after, .btn-toolbar:before, .btn-toolbar:after, .btn-group-vertical > .btn-group:before, .btn-group-vertical > .btn-group:after, .nav:before, .nav:after, .navbar:before, .navbar:after, .navbar-header:before, .navbar-header:after, .navbar-collapse:before, .navbar-collapse:after, .pager:before, .pager:after, .panel-body:before, .panel-body:after, .modal-header:before, .modal-header:after, .modal-footer:before, .modal-footer:after, .item\_buttons:before, .item\_buttons:after { content: " "; display: table; } .clearfix:after, .dl-horizontal dd:after, .container:after, .container-fluid:after, .row:after, .form-horizontal .form-group:after, .btn-toolbar:after, .btn-group-vertical > .btn-group:after, .nav:after, .navbar:after, .navbar-header:after, .navbar-collapse:after, .pager:after, .panel-body:after, .modal-header:after, .modal-footer:after, .item\_buttons:after { clear: both; } .center-block { display: block; margin-left: auto; margin-right: auto; } .pull-right { float: right !important; } .pull-left { float: left !important; } .hide { display: none !important; } .show { display: block !important; } .invisible { visibility: hidden; } .text-hide { font: 0/0 a; color: transparent; text-shadow: none; background-color: transparent; border: 0; } .hidden { display: none !important; } .affix { position: fixed; } @-ms-viewport { width: device-width; } .visible-xs, .visible-sm, .visible-md, .visible-lg { display: none !important; } .visible-xs-block, .visible-xs-inline, .visible-xs-inline-block, .visible-sm-block, .visible-sm-inline, .visible-sm-inline-block, .visible-md-block, .visible-md-inline, .visible-md-inline-block, .visible-lg-block, .visible-lg-inline, .visible-lg-inline-block { display: none !important; } @media (max-width: 767px) { .visible-xs { display: block !important; } table.visible-xs { display: table !important; } tr.visible-xs { display: table-row !important; } th.visible-xs, td.visible-xs { display: table-cell !important; } } @media (max-width: 767px) { .visible-xs-block { display: block !important; } } @media (max-width: 767px) { .visible-xs-inline { display: inline !important; } } @media (max-width: 767px) { .visible-xs-inline-block { display: inline-block !important; } } @media (min-width: 768px) and (max-width: 991px) { .visible-sm { display: block !important; } table.visible-sm { display: table !important; } tr.visible-sm { display: table-row !important; } th.visible-sm, td.visible-sm { display: table-cell !important; } } @media (min-width: 768px) and (max-width: 991px) { .visible-sm-block { display: block !important; } } @media (min-width: 768px) and (max-width: 991px) { .visible-sm-inline { display: inline !important; } } @media (min-width: 768px) and (max-width: 991px) { .visible-sm-inline-block { display: inline-block !important; } } @media (min-width: 992px) and (max-width: 1199px) { .visible-md { display: block !important; } table.visible-md { display: table !important; } tr.visible-md { display: table-row !important; } th.visible-md, td.visible-md { display: table-cell !important; } } @media (min-width: 992px) and (max-width: 1199px) { .visible-md-block { display: block !important; } } @media (min-width: 992px) and (max-width: 1199px) { .visible-md-inline { display: inline !important; } } @media (min-width: 992px) and (max-width: 1199px) { .visible-md-inline-block { display: inline-block !important; } } @media (min-width: 1200px) { .visible-lg { display: block !important; } table.visible-lg { display: table !important; } tr.visible-lg { display: table-row !important; } th.visible-lg, td.visible-lg { display: table-cell !important; } } @media (min-width: 1200px) { .visible-lg-block { display: block !important; } } @media (min-width: 1200px) { .visible-lg-inline { display: inline !important; } } @media (min-width: 1200px) { .visible-lg-inline-block { display: inline-block !important; } } @media (max-width: 767px) { .hidden-xs { display: none !important; } } @media (min-width: 768px) and (max-width: 991px) { .hidden-sm { display: none !important; } } @media (min-width: 992px) and (max-width: 1199px) { .hidden-md { display: none !important; } } @media (min-width: 1200px) { .hidden-lg { display: none !important; } } .visible-print { display: none !important; } @media print { .visible-print { display: block !important; } table.visible-print { display: table !important; } tr.visible-print { display: table-row !important; } th.visible-print, td.visible-print { display: table-cell !important; } } .visible-print-block { display: none !important; } @media print { .visible-print-block { display: block !important; } } .visible-print-inline { display: none !important; } @media print { .visible-print-inline { display: inline !important; } } .visible-print-inline-block { display: none !important; } @media print { .visible-print-inline-block { display: inline-block !important; } } @media print { .hidden-print { display: none !important; } } /*! * * Font Awesome * */ /*! * Font Awesome 4.2.0 by @davegandy - http://fontawesome.io - @fontawesome * License - http://fontawesome.io/license (Font: SIL OFL 1.1, CSS: MIT License) */ /* FONT PATH * -------------------------- */ @font-face { font-family: 'FontAwesome'; src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?v=4.2.0'); src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?#iefix&v=4.2.0') format('embedded-opentype'), url('../components/font-awesome/fonts/fontawesome-webfont.woff?v=4.2.0') format('woff'), url('../components/font-awesome/fonts/fontawesome-webfont.ttf?v=4.2.0') format('truetype'), url('../components/font-awesome/fonts/fontawesome-webfont.svg?v=4.2.0#fontawesomeregular') format('svg'); font-weight: normal; font-style: normal; } .fa { display: inline-block; font: normal normal normal 14px/1 FontAwesome; font-size: inherit; text-rendering: auto; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; } /* makes the font 33% larger relative to the icon container */ .fa-lg { font-size: 1.33333333em; line-height: 0.75em; vertical-align: -15%; } .fa-2x { font-size: 2em; } .fa-3x { font-size: 3em; } .fa-4x { font-size: 4em; } .fa-5x { font-size: 5em; } .fa-fw { width: 1.28571429em; text-align: center; } .fa-ul { padding-left: 0; margin-left: 2.14285714em; list-style-type: none; } .fa-ul > li { position: relative; } .fa-li { position: absolute; left: -2.14285714em; width: 2.14285714em; top: 0.14285714em; text-align: center; } .fa-li.fa-lg { left: -1.85714286em; } .fa-border { padding: .2em .25em .15em; border: solid 0.08em #eee; border-radius: .1em; } .pull-right { float: right; } .pull-left { float: left; } .fa.pull-left { margin-right: .3em; } .fa.pull-right { margin-left: .3em; } .fa-spin { -webkit-animation: fa-spin 2s infinite linear; animation: fa-spin 2s infinite linear; } @-webkit-keyframes fa-spin { 0% { -webkit-transform: rotate(0deg); transform: rotate(0deg); } 100% { -webkit-transform: rotate(359deg); transform: rotate(359deg); } } @keyframes fa-spin { 0% { -webkit-transform: rotate(0deg); transform: rotate(0deg); } 100% { -webkit-transform: rotate(359deg); transform: rotate(359deg); } } .fa-rotate-90 { filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=1); -webkit-transform: rotate(90deg); -ms-transform: rotate(90deg); transform: rotate(90deg); } .fa-rotate-180 { filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=2); -webkit-transform: rotate(180deg); -ms-transform: rotate(180deg); transform: rotate(180deg); } .fa-rotate-270 { filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=3); -webkit-transform: rotate(270deg); -ms-transform: rotate(270deg); transform: rotate(270deg); } .fa-flip-horizontal { filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=0, mirror=1); -webkit-transform: scale(-1, 1); -ms-transform: scale(-1, 1); transform: scale(-1, 1); } .fa-flip-vertical { filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=2, mirror=1); -webkit-transform: scale(1, -1); -ms-transform: scale(1, -1); transform: scale(1, -1); } :root .fa-rotate-90, :root .fa-rotate-180, :root .fa-rotate-270, :root .fa-flip-horizontal, :root .fa-flip-vertical { filter: none; } .fa-stack { position: relative; display: inline-block; width: 2em; height: 2em; line-height: 2em; vertical-align: middle; } .fa-stack-1x, .fa-stack-2x { position: absolute; left: 0; width: 100%; text-align: center; } .fa-stack-1x { line-height: inherit; } .fa-stack-2x { font-size: 2em; } .fa-inverse { color: #fff; } /* Font Awesome uses the Unicode Private Use Area (PUA) to ensure screen readers do not read off random characters that represent icons */ .fa-glass:before { content: "\\f000"; } .fa-music:before { content: "\\f001"; } .fa-search:before { content: "\\f002"; } .fa-envelope-o:before { content: "\\f003"; } .fa-heart:before { content: "\\f004"; } .fa-star:before { content: "\\f005"; } .fa-star-o:before { content: "\\f006"; } .fa-user:before { content: "\\f007"; } .fa-film:before { content: "\\f008"; } .fa-th-large:before { content: "\\f009"; } .fa-th:before { content: "\\f00a"; } .fa-th-list:before { content: "\\f00b"; } .fa-check:before { content: "\\f00c"; } .fa-remove:before, .fa-close:before, .fa-times:before { content: "\\f00d"; } .fa-search-plus:before { content: "\\f00e"; } .fa-search-minus:before { content: "\\f010"; } .fa-power-off:before { content: "\\f011"; } .fa-signal:before { content: "\\f012"; } .fa-gear:before, .fa-cog:before { content: "\\f013"; } .fa-trash-o:before { content: "\\f014"; } .fa-home:before { content: "\\f015"; } .fa-file-o:before { content: "\\f016"; } .fa-clock-o:before { content: "\\f017"; } .fa-road:before { content: "\\f018"; } .fa-download:before { content: "\\f019"; } .fa-arrow-circle-o-down:before { content: "\\f01a"; } .fa-arrow-circle-o-up:before { content: "\\f01b"; } .fa-inbox:before { content: "\\f01c"; } .fa-play-circle-o:before { content: "\\f01d"; } .fa-rotate-right:before, .fa-repeat:before { content: "\\f01e"; } .fa-refresh:before { content: "\\f021"; } .fa-list-alt:before { content: "\\f022"; } .fa-lock:before { content: "\\f023"; } .fa-flag:before { content: "\\f024"; } .fa-headphones:before { content: "\\f025"; } .fa-volume-off:before { content: "\\f026"; } .fa-volume-down:before { content: "\\f027"; } .fa-volume-up:before { content: "\\f028"; } .fa-qrcode:before { content: "\\f029"; } .fa-barcode:before { content: "\\f02a"; } .fa-tag:before { content: "\\f02b"; } .fa-tags:before { content: "\\f02c"; } .fa-book:before { content: "\\f02d"; } .fa-bookmark:before { content: "\\f02e"; } .fa-print:before { content: "\\f02f"; } .fa-camera:before { content: "\\f030"; } .fa-font:before { content: "\\f031"; } .fa-bold:before { content: "\\f032"; } .fa-italic:before { content: "\\f033"; } .fa-text-height:before { content: "\\f034"; } .fa-text-width:before { content: "\\f035"; } .fa-align-left:before { content: "\\f036"; } .fa-align-center:before { content: "\\f037"; } .fa-align-right:before { content: "\\f038"; } .fa-align-justify:before { content: "\\f039"; } .fa-list:before { content: "\\f03a"; } .fa-dedent:before, .fa-outdent:before { content: "\\f03b"; } .fa-indent:before { content: "\\f03c"; } .fa-video-camera:before { content: "\\f03d"; } .fa-photo:before, .fa-image:before, .fa-picture-o:before { content: "\\f03e"; } .fa-pencil:before { content: "\\f040"; } .fa-map-marker:before { content: "\\f041"; } .fa-adjust:before { content: "\\f042"; } .fa-tint:before { content: "\\f043"; } .fa-edit:before, .fa-pencil-square-o:before { content: "\\f044"; } .fa-share-square-o:before { content: "\\f045"; } .fa-check-square-o:before { content: "\\f046"; } .fa-arrows:before { content: "\\f047"; } .fa-step-backward:before { content: "\\f048"; } .fa-fast-backward:before { content: "\\f049"; } .fa-backward:before { content: "\\f04a"; } .fa-play:before { content: "\\f04b"; } .fa-pause:before { content: "\\f04c"; } .fa-stop:before { content: "\\f04d"; } .fa-forward:before { content: "\\f04e"; } .fa-fast-forward:before { content: "\\f050"; } .fa-step-forward:before { content: "\\f051"; } .fa-eject:before { content: "\\f052"; } .fa-chevron-left:before { content: "\\f053"; } .fa-chevron-right:before { content: "\\f054"; } .fa-plus-circle:before { content: "\\f055"; } .fa-minus-circle:before { content: "\\f056"; } .fa-times-circle:before { content: "\\f057"; } .fa-check-circle:before { content: "\\f058"; } .fa-question-circle:before { content: "\\f059"; } .fa-info-circle:before { content: "\\f05a"; } .fa-crosshairs:before { content: "\\f05b"; } .fa-times-circle-o:before { content: "\\f05c"; } .fa-check-circle-o:before { content: "\\f05d"; } .fa-ban:before { content: "\\f05e"; } .fa-arrow-left:before { content: "\\f060"; } .fa-arrow-right:before { content: "\\f061"; } .fa-arrow-up:before { content: "\\f062"; } .fa-arrow-down:before { content: "\\f063"; } .fa-mail-forward:before, .fa-share:before { content: "\\f064"; } .fa-expand:before { content: "\\f065"; } .fa-compress:before { content: "\\f066"; } .fa-plus:before { content: "\\f067"; } .fa-minus:before { content: "\\f068"; } .fa-asterisk:before { content: "\\f069"; } .fa-exclamation-circle:before { content: "\\f06a"; } .fa-gift:before { content: "\\f06b"; } .fa-leaf:before { content: "\\f06c"; } .fa-fire:before { content: "\\f06d"; } .fa-eye:before { content: "\\f06e"; } .fa-eye-slash:before { content: "\\f070"; } .fa-warning:before, .fa-exclamation-triangle:before { content: "\\f071"; } .fa-plane:before { content: "\\f072"; } .fa-calendar:before { content: "\\f073"; } .fa-random:before { content: "\\f074"; } .fa-comment:before { content: "\\f075"; } .fa-magnet:before { content: "\\f076"; } .fa-chevron-up:before { content: "\\f077"; } .fa-chevron-down:before { content: "\\f078"; } .fa-retweet:before { content: "\\f079"; } .fa-shopping-cart:before { content: "\\f07a"; } .fa-folder:before { content: "\\f07b"; } .fa-folder-open:before { content: "\\f07c"; } .fa-arrows-v:before { content: "\\f07d"; } .fa-arrows-h:before { content: "\\f07e"; } .fa-bar-chart-o:before, .fa-bar-chart:before { content: "\\f080"; } .fa-twitter-square:before { content: "\\f081"; } .fa-facebook-square:before { content: "\\f082"; } .fa-camera-retro:before { content: "\\f083"; } .fa-key:before { content: "\\f084"; } .fa-gears:before, .fa-cogs:before { content: "\\f085"; } .fa-comments:before { content: "\\f086"; } .fa-thumbs-o-up:before { content: "\\f087"; } .fa-thumbs-o-down:before { content: "\\f088"; } .fa-star-half:before { content: "\\f089"; } .fa-heart-o:before { content: "\\f08a"; } .fa-sign-out:before { content: "\\f08b"; } .fa-linkedin-square:before { content: "\\f08c"; } .fa-thumb-tack:before { content: "\\f08d"; } .fa-external-link:before { content: "\\f08e"; } .fa-sign-in:before { content: "\\f090"; } .fa-trophy:before { content: "\\f091"; } .fa-github-square:before { content: "\\f092"; } .fa-upload:before { content: "\\f093"; } .fa-lemon-o:before { content: "\\f094"; } .fa-phone:before { content: "\\f095"; } .fa-square-o:before { content: "\\f096"; } .fa-bookmark-o:before { content: "\\f097"; } .fa-phone-square:before { content: "\\f098"; } .fa-twitter:before { content: "\\f099"; } .fa-facebook:before { content: "\\f09a"; } .fa-github:before { content: "\\f09b"; } .fa-unlock:before { content: "\\f09c"; } .fa-credit-card:before { content: "\\f09d"; } .fa-rss:before { content: "\\f09e"; } .fa-hdd-o:before { content: "\\f0a0"; } .fa-bullhorn:before { content: "\\f0a1"; } .fa-bell:before { content: "\\f0f3"; } .fa-certificate:before { content: "\\f0a3"; } .fa-hand-o-right:before { content: "\\f0a4"; } .fa-hand-o-left:before { content: "\\f0a5"; } .fa-hand-o-up:before { content: "\\f0a6"; } .fa-hand-o-down:before { content: "\\f0a7"; } .fa-arrow-circle-left:before { content: "\\f0a8"; } .fa-arrow-circle-right:before { content: "\\f0a9"; } .fa-arrow-circle-up:before { content: "\\f0aa"; } .fa-arrow-circle-down:before { content: "\\f0ab"; } .fa-globe:before { content: "\\f0ac"; } .fa-wrench:before { content: "\\f0ad"; } .fa-tasks:before { content: "\\f0ae"; } .fa-filter:before { content: "\\f0b0"; } .fa-briefcase:before { content: "\\f0b1"; } .fa-arrows-alt:before { content: "\\f0b2"; } .fa-group:before, .fa-users:before { content: "\\f0c0"; } .fa-chain:before, .fa-link:before { content: "\\f0c1"; } .fa-cloud:before { content: "\\f0c2"; } .fa-flask:before { content: "\\f0c3"; } .fa-cut:before, .fa-scissors:before { content: "\\f0c4"; } .fa-copy:before, .fa-files-o:before { content: "\\f0c5"; } .fa-paperclip:before { content: "\\f0c6"; } .fa-save:before, .fa-floppy-o:before { content: "\\f0c7"; } .fa-square:before { content: "\\f0c8"; } .fa-navicon:before, .fa-reorder:before, .fa-bars:before { content: "\\f0c9"; } .fa-list-ul:before { content: "\\f0ca"; } .fa-list-ol:before { content: "\\f0cb"; } .fa-strikethrough:before { content: "\\f0cc"; } .fa-underline:before { content: "\\f0cd"; } .fa-table:before { content: "\\f0ce"; } .fa-magic:before { content: "\\f0d0"; } .fa-truck:before { content: "\\f0d1"; } .fa-pinterest:before { content: "\\f0d2"; } .fa-pinterest-square:before { content: "\\f0d3"; } .fa-google-plus-square:before { content: "\\f0d4"; } .fa-google-plus:before { content: "\\f0d5"; } .fa-money:before { content: "\\f0d6"; } .fa-caret-down:before { content: "\\f0d7"; } .fa-caret-up:before { content: "\\f0d8"; } .fa-caret-left:before { content: "\\f0d9"; } .fa-caret-right:before { content: "\\f0da"; } .fa-columns:before { content: "\\f0db"; } .fa-unsorted:before, .fa-sort:before { content: "\\f0dc"; } .fa-sort-down:before, .fa-sort-desc:before { content: "\\f0dd"; } .fa-sort-up:before, .fa-sort-asc:before { content: "\\f0de"; } .fa-envelope:before { content: "\\f0e0"; } .fa-linkedin:before { content: "\\f0e1"; } .fa-rotate-left:before, .fa-undo:before { content: "\\f0e2"; } .fa-legal:before, .fa-gavel:before { content: "\\f0e3"; } .fa-dashboard:before, .fa-tachometer:before { content: "\\f0e4"; } .fa-comment-o:before { content: "\\f0e5"; } .fa-comments-o:before { content: "\\f0e6"; } .fa-flash:before, .fa-bolt:before { content: "\\f0e7"; } .fa-sitemap:before { content: "\\f0e8"; } .fa-umbrella:before { content: "\\f0e9"; } .fa-paste:before, .fa-clipboard:before { content: "\\f0ea"; } .fa-lightbulb-o:before { content: "\\f0eb"; } .fa-exchange:before { content: "\\f0ec"; } .fa-cloud-download:before { content: "\\f0ed"; } .fa-cloud-upload:before { content: "\\f0ee"; } .fa-user-md:before { content: "\\f0f0"; } .fa-stethoscope:before { content: "\\f0f1"; } .fa-suitcase:before { content: "\\f0f2"; } .fa-bell-o:before { content: "\\f0a2"; } .fa-coffee:before { content: "\\f0f4"; } .fa-cutlery:before { content: "\\f0f5"; } .fa-file-text-o:before { content: "\\f0f6"; } .fa-building-o:before { content: "\\f0f7"; } .fa-hospital-o:before { content: "\\f0f8"; } .fa-ambulance:before { content: "\\f0f9"; } .fa-medkit:before { content: "\\f0fa"; } .fa-fighter-jet:before { content: "\\f0fb"; } .fa-beer:before { content: "\\f0fc"; } .fa-h-square:before { content: "\\f0fd"; } .fa-plus-square:before { content: "\\f0fe"; } .fa-angle-double-left:before { content: "\\f100"; } .fa-angle-double-right:before { content: "\\f101"; } .fa-angle-double-up:before { content: "\\f102"; } .fa-angle-double-down:before { content: "\\f103"; } .fa-angle-left:before { content: "\\f104"; } .fa-angle-right:before { content: "\\f105"; } .fa-angle-up:before { content: "\\f106"; } .fa-angle-down:before { content: "\\f107"; } .fa-desktop:before { content: "\\f108"; } .fa-laptop:before { content: "\\f109"; } .fa-tablet:before { content: "\\f10a"; } .fa-mobile-phone:before, .fa-mobile:before { content: "\\f10b"; } .fa-circle-o:before { content: "\\f10c"; } .fa-quote-left:before { content: "\\f10d"; } .fa-quote-right:before { content: "\\f10e"; } .fa-spinner:before { content: "\\f110"; } .fa-circle:before { content: "\\f111"; } .fa-mail-reply:before, .fa-reply:before { content: "\\f112"; } .fa-github-alt:before { content: "\\f113"; } .fa-folder-o:before { content: "\\f114"; } .fa-folder-open-o:before { content: "\\f115"; } .fa-smile-o:before { content: "\\f118"; } .fa-frown-o:before { content: "\\f119"; } .fa-meh-o:before { content: "\\f11a"; } .fa-gamepad:before { content: "\\f11b"; } .fa-keyboard-o:before { content: "\\f11c"; } .fa-flag-o:before { content: "\\f11d"; } .fa-flag-checkered:before { content: "\\f11e"; } .fa-terminal:before { content: "\\f120"; } .fa-code:before { content: "\\f121"; } .fa-mail-reply-all:before, .fa-reply-all:before { content: "\\f122"; } .fa-star-half-empty:before, .fa-star-half-full:before, .fa-star-half-o:before { content: "\\f123"; } .fa-location-arrow:before { content: "\\f124"; } .fa-crop:before { content: "\\f125"; } .fa-code-fork:before { content: "\\f126"; } .fa-unlink:before, .fa-chain-broken:before { content: "\\f127"; } .fa-question:before { content: "\\f128"; } .fa-info:before { content: "\\f129"; } .fa-exclamation:before { content: "\\f12a"; } .fa-superscript:before { content: "\\f12b"; } .fa-subscript:before { content: "\\f12c"; } .fa-eraser:before { content: "\\f12d"; } .fa-puzzle-piece:before { content: "\\f12e"; } .fa-microphone:before { content: "\\f130"; } .fa-microphone-slash:before { content: "\\f131"; } .fa-shield:before { content: "\\f132"; } .fa-calendar-o:before { content: "\\f133"; } .fa-fire-extinguisher:before { content: "\\f134"; } .fa-rocket:before { content: "\\f135"; } .fa-maxcdn:before { content: "\\f136"; } .fa-chevron-circle-left:before { content: "\\f137"; } .fa-chevron-circle-right:before { content: "\\f138"; } .fa-chevron-circle-up:before { content: "\\f139"; } .fa-chevron-circle-down:before { content: "\\f13a"; } .fa-html5:before { content: "\\f13b"; } .fa-css3:before { content: "\\f13c"; } .fa-anchor:before { content: "\\f13d"; } .fa-unlock-alt:before { content: "\\f13e"; } .fa-bullseye:before { content: "\\f140"; } .fa-ellipsis-h:before { content: "\\f141"; } .fa-ellipsis-v:before { content: "\\f142"; } .fa-rss-square:before { content: "\\f143"; } .fa-play-circle:before { content: "\\f144"; } .fa-ticket:before { content: "\\f145"; } .fa-minus-square:before { content: "\\f146"; } .fa-minus-square-o:before { content: "\\f147"; } .fa-level-up:before { content: "\\f148"; } .fa-level-down:before { content: "\\f149"; } .fa-check-square:before { content: "\\f14a"; } .fa-pencil-square:before { content: "\\f14b"; } .fa-external-link-square:before { content: "\\f14c"; } .fa-share-square:before { content: "\\f14d"; } .fa-compass:before { content: "\\f14e"; } .fa-toggle-down:before, .fa-caret-square-o-down:before { content: "\\f150"; } .fa-toggle-up:before, .fa-caret-square-o-up:before { content: "\\f151"; } .fa-toggle-right:before, .fa-caret-square-o-right:before { content: "\\f152"; } .fa-euro:before, .fa-eur:before { content: "\\f153"; } .fa-gbp:before { content: "\\f154"; } .fa-dollar:before, .fa-usd:before { content: "\\f155"; } .fa-rupee:before, .fa-inr:before { content: "\\f156"; } .fa-cny:before, .fa-rmb:before, .fa-yen:before, .fa-jpy:before { content: "\\f157"; } .fa-ruble:before, .fa-rouble:before, .fa-rub:before { content: "\\f158"; } .fa-won:before, .fa-krw:before { content: "\\f159"; } .fa-bitcoin:before, .fa-btc:before { content: "\\f15a"; } .fa-file:before { content: "\\f15b"; } .fa-file-text:before { content: "\\f15c"; } .fa-sort-alpha-asc:before { content: "\\f15d"; } .fa-sort-alpha-desc:before { content: "\\f15e"; } .fa-sort-amount-asc:before { content: "\\f160"; } .fa-sort-amount-desc:before { content: "\\f161"; } .fa-sort-numeric-asc:before { content: "\\f162"; } .fa-sort-numeric-desc:before { content: "\\f163"; } .fa-thumbs-up:before { content: "\\f164"; } .fa-thumbs-down:before { content: "\\f165"; } .fa-youtube-square:before { content: "\\f166"; } .fa-youtube:before { content: "\\f167"; } .fa-xing:before { content: "\\f168"; } .fa-xing-square:before { content: "\\f169"; } .fa-youtube-play:before { content: "\\f16a"; } .fa-dropbox:before { content: "\\f16b"; } .fa-stack-overflow:before { content: "\\f16c"; } .fa-instagram:before { content: "\\f16d"; } .fa-flickr:before { content: "\\f16e"; } .fa-adn:before { content: "\\f170"; } .fa-bitbucket:before { content: "\\f171"; } .fa-bitbucket-square:before { content: "\\f172"; } .fa-tumblr:before { content: "\\f173"; } .fa-tumblr-square:before { content: "\\f174"; } .fa-long-arrow-down:before { content: "\\f175"; } .fa-long-arrow-up:before { content: "\\f176"; } .fa-long-arrow-left:before { content: "\\f177"; } .fa-long-arrow-right:before { content: "\\f178"; } .fa-apple:before { content: "\\f179"; } .fa-windows:before { content: "\\f17a"; } .fa-android:before { content: "\\f17b"; } .fa-linux:before { content: "\\f17c"; } .fa-dribbble:before { content: "\\f17d"; } .fa-skype:before { content: "\\f17e"; } .fa-foursquare:before { content: "\\f180"; } .fa-trello:before { content: "\\f181"; } .fa-female:before { content: "\\f182"; } .fa-male:before { content: "\\f183"; } .fa-gittip:before { content: "\\f184"; } .fa-sun-o:before { content: "\\f185"; } .fa-moon-o:before { content: "\\f186"; } .fa-archive:before { content: "\\f187"; } .fa-bug:before { content: "\\f188"; } .fa-vk:before { content: "\\f189"; } .fa-weibo:before { content: "\\f18a"; } .fa-renren:before { content: "\\f18b"; } .fa-pagelines:before { content: "\\f18c"; } .fa-stack-exchange:before { content: "\\f18d"; } .fa-arrow-circle-o-right:before { content: "\\f18e"; } .fa-arrow-circle-o-left:before { content: "\\f190"; } .fa-toggle-left:before, .fa-caret-square-o-left:before { content: "\\f191"; } .fa-dot-circle-o:before { content: "\\f192"; } .fa-wheelchair:before { content: "\\f193"; } .fa-vimeo-square:before { content: "\\f194"; } .fa-turkish-lira:before, .fa-try:before { content: "\\f195"; } .fa-plus-square-o:before { content: "\\f196"; } .fa-space-shuttle:before { content: "\\f197"; } .fa-slack:before { content: "\\f198"; } .fa-envelope-square:before { content: "\\f199"; } .fa-wordpress:before { content: "\\f19a"; } .fa-openid:before { content: "\\f19b"; } .fa-institution:before, .fa-bank:before, .fa-university:before { content: "\\f19c"; } .fa-mortar-board:before, .fa-graduation-cap:before { content: "\\f19d"; } .fa-yahoo:before { content: "\\f19e"; } .fa-google:before { content: "\\f1a0"; } .fa-reddit:before { content: "\\f1a1"; } .fa-reddit-square:before { content: "\\f1a2"; } .fa-stumbleupon-circle:before { content: "\\f1a3"; } .fa-stumbleupon:before { content: "\\f1a4"; } .fa-delicious:before { content: "\\f1a5"; } .fa-digg:before { content: "\\f1a6"; } .fa-pied-piper:before { content: "\\f1a7"; } .fa-pied-piper-alt:before { content: "\\f1a8"; } .fa-drupal:before { content: "\\f1a9"; } .fa-joomla:before { content: "\\f1aa"; } .fa-language:before { content: "\\f1ab"; } .fa-fax:before { content: "\\f1ac"; } .fa-building:before { content: "\\f1ad"; } .fa-child:before { content: "\\f1ae"; } .fa-paw:before { content: "\\f1b0"; } .fa-spoon:before { content: "\\f1b1"; } .fa-cube:before { content: "\\f1b2"; } .fa-cubes:before { content: "\\f1b3"; } .fa-behance:before { content: "\\f1b4"; } .fa-behance-square:before { content: "\\f1b5"; } .fa-steam:before { content: "\\f1b6"; } .fa-steam-square:before { content: "\\f1b7"; } .fa-recycle:before { content: "\\f1b8"; } .fa-automobile:before, .fa-car:before { content: "\\f1b9"; } .fa-cab:before, .fa-taxi:before { content: "\\f1ba"; } .fa-tree:before { content: "\\f1bb"; } .fa-spotify:before { content: "\\f1bc"; } .fa-deviantart:before { content: "\\f1bd"; } .fa-soundcloud:before { content: "\\f1be"; } .fa-database:before { content: "\\f1c0"; } .fa-file-pdf-o:before { content: "\\f1c1"; } .fa-file-word-o:before { content: "\\f1c2"; } .fa-file-excel-o:before { content: "\\f1c3"; } .fa-file-powerpoint-o:before { content: "\\f1c4"; } .fa-file-photo-o:before, .fa-file-picture-o:before, .fa-file-image-o:before { content: "\\f1c5"; } .fa-file-zip-o:before, .fa-file-archive-o:before { content: "\\f1c6"; } .fa-file-sound-o:before, .fa-file-audio-o:before { content: "\\f1c7"; } .fa-file-movie-o:before, .fa-file-video-o:before { content: "\\f1c8"; } .fa-file-code-o:before { content: "\\f1c9"; } .fa-vine:before { content: "\\f1ca"; } .fa-codepen:before { content: "\\f1cb"; } .fa-jsfiddle:before { content: "\\f1cc"; } .fa-life-bouy:before, .fa-life-buoy:before, .fa-life-saver:before, .fa-support:before, .fa-life-ring:before { content: "\\f1cd"; } .fa-circle-o-notch:before { content: "\\f1ce"; } .fa-ra:before, .fa-rebel:before { content: "\\f1d0"; } .fa-ge:before, .fa-empire:before { content: "\\f1d1"; } .fa-git-square:before { content: "\\f1d2"; } .fa-git:before { content: "\\f1d3"; } .fa-hacker-news:before { content: "\\f1d4"; } .fa-tencent-weibo:before { content: "\\f1d5"; } .fa-qq:before { content: "\\f1d6"; } .fa-wechat:before, .fa-weixin:before { content: "\\f1d7"; } .fa-send:before, .fa-paper-plane:before { content: "\\f1d8"; } .fa-send-o:before, .fa-paper-plane-o:before { content: "\\f1d9"; } .fa-history:before { content: "\\f1da"; } .fa-circle-thin:before { content: "\\f1db"; } .fa-header:before { content: "\\f1dc"; } .fa-paragraph:before { content: "\\f1dd"; } .fa-sliders:before { content: "\\f1de"; } .fa-share-alt:before { content: "\\f1e0"; } .fa-share-alt-square:before { content: "\\f1e1"; } .fa-bomb:before { content: "\\f1e2"; } .fa-soccer-ball-o:before, .fa-futbol-o:before { content: "\\f1e3"; } .fa-tty:before { content: "\\f1e4"; } .fa-binoculars:before { content: "\\f1e5"; } .fa-plug:before { content: "\\f1e6"; } .fa-slideshare:before { content: "\\f1e7"; } .fa-twitch:before { content: "\\f1e8"; } .fa-yelp:before { content: "\\f1e9"; } .fa-newspaper-o:before { content: "\\f1ea"; } .fa-wifi:before { content: "\\f1eb"; } .fa-calculator:before { content: "\\f1ec"; } .fa-paypal:before { content: "\\f1ed"; } .fa-google-wallet:before { content: "\\f1ee"; } .fa-cc-visa:before { content: "\\f1f0"; } .fa-cc-mastercard:before { content: "\\f1f1"; } .fa-cc-discover:before { content: "\\f1f2"; } .fa-cc-amex:before { content: "\\f1f3"; } .fa-cc-paypal:before { content: "\\f1f4"; } .fa-cc-stripe:before { content: "\\f1f5"; } .fa-bell-slash:before { content: "\\f1f6"; } .fa-bell-slash-o:before { content: "\\f1f7"; } .fa-trash:before { content: "\\f1f8"; } .fa-copyright:before { content: "\\f1f9"; } .fa-at:before { content: "\\f1fa"; } .fa-eyedropper:before { content: "\\f1fb"; } .fa-paint-brush:before { content: "\\f1fc"; } .fa-birthday-cake:before { content: "\\f1fd"; } .fa-area-chart:before { content: "\\f1fe"; } .fa-pie-chart:before { content: "\\f200"; } .fa-line-chart:before { content: "\\f201"; } .fa-lastfm:before { content: "\\f202"; } .fa-lastfm-square:before { content: "\\f203"; } .fa-toggle-off:before { content: "\\f204"; } .fa-toggle-on:before { content: "\\f205"; } .fa-bicycle:before { content: "\\f206"; } .fa-bus:before { content: "\\f207"; } .fa-ioxhost:before { content: "\\f208"; } .fa-angellist:before { content: "\\f209"; } .fa-cc:before { content: "\\f20a"; } .fa-shekel:before, .fa-sheqel:before, .fa-ils:before { content: "\\f20b"; } .fa-meanpath:before { content: "\\f20c"; } /*! * * IPython base * */ .modal.fade .modal-dialog { -webkit-transform: translate(0, 0); -ms-transform: translate(0, 0); -o-transform: translate(0, 0); transform: translate(0, 0); } code { color: #000; } pre { font-size: inherit; line-height: inherit; } label { font-weight: normal; } /* Make the page background atleast 100% the height of the view port */ /* Make the page itself atleast 70% the height of the view port */ .border-box-sizing { box-sizing: border-box; -moz-box-sizing: border-box; -webkit-box-sizing: border-box; } .corner-all { border-radius: 2px; } .no-padding { padding: 0px; } /* Flexible box model classes */ /* Taken from Alex Russell http://infrequently.org/2009/08/css-3-progress/ */ /* This file is a compatability layer. It allows the usage of flexible box model layouts accross multiple browsers, including older browsers. The newest, universal implementation of the flexible box model is used when available (see \`Modern browsers\` comments below). Browsers that are known to implement this new spec completely include: Firefox 28.0+ Chrome 29.0+ Internet Explorer 11+ Opera 17.0+ Browsers not listed, including Safari, are supported via the styling under the \`Old browsers\` comments below. */ .hbox { /* Old browsers */ display: -webkit-box; -webkit-box-orient: horizontal; -webkit-box-align: stretch; display: -moz-box; -moz-box-orient: horizontal; -moz-box-align: stretch; display: box; box-orient: horizontal; box-align: stretch; /* Modern browsers */ display: flex; flex-direction: row; align-items: stretch; } .hbox > * { /* Old browsers */ -webkit-box-flex: 0; -moz-box-flex: 0; box-flex: 0; /* Modern browsers */ flex: none; } .vbox { /* Old browsers */ display: -webkit-box; -webkit-box-orient: vertical; -webkit-box-align: stretch; display: -moz-box; -moz-box-orient: vertical; -moz-box-align: stretch; display: box; box-orient: vertical; box-align: stretch; /* Modern browsers */ display: flex; flex-direction: column; align-items: stretch; } .vbox > * { /* Old browsers */ -webkit-box-flex: 0; -moz-box-flex: 0; box-flex: 0; /* Modern browsers */ flex: none; } .hbox.reverse, .vbox.reverse, .reverse { /* Old browsers */ -webkit-box-direction: reverse; -moz-box-direction: reverse; box-direction: reverse; /* Modern browsers */ flex-direction: row-reverse; } .hbox.box-flex0, .vbox.box-flex0, .box-flex0 { /* Old browsers */ -webkit-box-flex: 0; -moz-box-flex: 0; box-flex: 0; /* Modern browsers */ flex: none; width: auto; } .hbox.box-flex1, .vbox.box-flex1, .box-flex1 { /* Old browsers */ -webkit-box-flex: 1; -moz-box-flex: 1; box-flex: 1; /* Modern browsers */ flex: 1; } .hbox.box-flex, .vbox.box-flex, .box-flex { /* Old browsers */ /* Old browsers */ -webkit-box-flex: 1; -moz-box-flex: 1; box-flex: 1; /* Modern browsers */ flex: 1; } .hbox.box-flex2, .vbox.box-flex2, .box-flex2 { /* Old browsers */ -webkit-box-flex: 2; -moz-box-flex: 2; box-flex: 2; /* Modern browsers */ flex: 2; } .box-group1 { /* Deprecated */ -webkit-box-flex-group: 1; -moz-box-flex-group: 1; box-flex-group: 1; } .box-group2 { /* Deprecated */ -webkit-box-flex-group: 2; -moz-box-flex-group: 2; box-flex-group: 2; } .hbox.start, .vbox.start, .start { /* Old browsers */ -webkit-box-pack: start; -moz-box-pack: start; box-pack: start; /* Modern browsers */ justify-content: flex-start; } .hbox.end, .vbox.end, .end { /* Old browsers */ -webkit-box-pack: end; -moz-box-pack: end; box-pack: end; /* Modern browsers */ justify-content: flex-end; } .hbox.center, .vbox.center, .center { /* Old browsers */ -webkit-box-pack: center; -moz-box-pack: center; box-pack: center; /* Modern browsers */ justify-content: center; } .hbox.baseline, .vbox.baseline, .baseline { /* Old browsers */ -webkit-box-pack: baseline; -moz-box-pack: baseline; box-pack: baseline; /* Modern browsers */ justify-content: baseline; } .hbox.stretch, .vbox.stretch, .stretch { /* Old browsers */ -webkit-box-pack: stretch; -moz-box-pack: stretch; box-pack: stretch; /* Modern browsers */ justify-content: stretch; } .hbox.align-start, .vbox.align-start, .align-start { /* Old browsers */ -webkit-box-align: start; -moz-box-align: start; box-align: start; /* Modern browsers */ align-items: flex-start; } .hbox.align-end, .vbox.align-end, .align-end { /* Old browsers */ -webkit-box-align: end; -moz-box-align: end; box-align: end; /* Modern browsers */ align-items: flex-end; } .hbox.align-center, .vbox.align-center, .align-center { /* Old browsers */ -webkit-box-align: center; -moz-box-align: center; box-align: center; /* Modern browsers */ align-items: center; } .hbox.align-baseline, .vbox.align-baseline, .align-baseline { /* Old browsers */ -webkit-box-align: baseline; -moz-box-align: baseline; box-align: baseline; /* Modern browsers */ align-items: baseline; } .hbox.align-stretch, .vbox.align-stretch, .align-stretch { /* Old browsers */ -webkit-box-align: stretch; -moz-box-align: stretch; box-align: stretch; /* Modern browsers */ align-items: stretch; } div.error { margin: 2em; text-align: center; } div.error > h1 { font-size: 500%; line-height: normal; } div.error > p { font-size: 200%; line-height: normal; } div.traceback-wrapper { text-align: left; max-width: 800px; margin: auto; } /** * Primary styles * * Author: Jupyter Development Team */ body { background-color: #fff; /* This makes sure that the body covers the entire window and needs to be in a different element than the display: box in wrapper below */ position: absolute; left: 0px; right: 0px; top: 0px; bottom: 0px; overflow: visible; } body > #header { /* Initially hidden to prevent FLOUC */ display: none; background-color: #fff; /* Display over codemirror */ position: relative; z-index: 100; } body > #header #header-container { padding-bottom: 5px; padding-top: 5px; box-sizing: border-box; -moz-box-sizing: border-box; -webkit-box-sizing: border-box; } body > #header .header-bar { width: 100%; height: 1px; background: #e7e7e7; margin-bottom: -1px; } @media print { body > #header { display: none !important; } } #header-spacer { width: 100%; visibility: hidden; } @media print { #header-spacer { display: none; } } #ipython\_notebook { padding-left: 0px; padding-top: 1px; padding-bottom: 1px; } @media (max-width: 991px) { #ipython\_notebook { margin-left: 10px; } } \[dir="rtl"\] #ipython\_notebook { float: right !important; } #noscript { width: auto; padding-top: 16px; padding-bottom: 16px; text-align: center; font-size: 22px; color: red; font-weight: bold; } #ipython\_notebook img { height: 28px; } #site { width: 100%; display: none; box-sizing: border-box; -moz-box-sizing: border-box; -webkit-box-sizing: border-box; overflow: auto; } @media print { #site { height: auto !important; } } /* Smaller buttons */ .ui-button .ui-button-text { padding: 0.2em 0.8em; font-size: 77%; } input.ui-button { padding: 0.3em 0.9em; } span#login\_widget { float: right; } span#login\_widget > .button, #logout { color: #333; background-color: #fff; border-color: #ccc; } span#login\_widget > .button:focus, #logout:focus, span#login\_widget > .button.focus, #logout.focus { color: #333; background-color: #e6e6e6; border-color: #8c8c8c; } span#login\_widget > .button:hover, #logout:hover { color: #333; background-color: #e6e6e6; border-color: #adadad; } span#login\_widget > .button:active, #logout:active, span#login\_widget > .button.active, #logout.active, .open > .dropdown-togglespan#login\_widget > .button, .open > .dropdown-toggle#logout { color: #333; background-color: #e6e6e6; border-color: #adadad; } span#login\_widget > .button:active:hover, #logout:active:hover, span#login\_widget > .button.active:hover, #logout.active:hover, .open > .dropdown-togglespan#login\_widget > .button:hover, .open > .dropdown-toggle#logout:hover, span#login\_widget > .button:active:focus, #logout:active:focus, span#login\_widget > .button.active:focus, #logout.active:focus, .open > .dropdown-togglespan#login\_widget > .button:focus, .open > .dropdown-toggle#logout:focus, span#login\_widget > .button:active.focus, #logout:active.focus, span#login\_widget > .button.active.focus, #logout.active.focus, .open > .dropdown-togglespan#login\_widget > .button.focus, .open > .dropdown-toggle#logout.focus { color: #333; background-color: #d4d4d4; border-color: #8c8c8c; } span#login\_widget > .button:active, #logout:active, span#login\_widget > .button.active, #logout.active, .open > .dropdown-togglespan#login\_widget > .button, .open > .dropdown-toggle#logout { background-image: none; } span#login\_widget > .button.disabled:hover, #logout.disabled:hover, span#login\_widget > .button\[disabled\]:hover, #logout\[disabled\]:hover, fieldset\[disabled\] span#login\_widget > .button:hover, fieldset\[disabled\] #logout:hover, span#login\_widget > .button.disabled:focus, #logout.disabled:focus, span#login\_widget > .button\[disabled\]:focus, #logout\[disabled\]:focus, fieldset\[disabled\] span#login\_widget > .button:focus, fieldset\[disabled\] #logout:focus, span#login\_widget > .button.disabled.focus, #logout.disabled.focus, span#login\_widget > .button\[disabled\].focus, #logout\[disabled\].focus, fieldset\[disabled\] span#login\_widget > .button.focus, fieldset\[disabled\] #logout.focus { background-color: #fff; border-color: #ccc; } span#login\_widget > .button .badge, #logout .badge { color: #fff; background-color: #333; } .nav-header { text-transform: none; } #header > span { margin-top: 10px; } .modal\_stretch .modal-dialog { /* Old browsers */ display: -webkit-box; -webkit-box-orient: vertical; -webkit-box-align: stretch; display: -moz-box; -moz-box-orient: vertical; -moz-box-align: stretch; display: box; box-orient: vertical; box-align: stretch; /* Modern browsers */ display: flex; flex-direction: column; align-items: stretch; min-height: 80vh; } .modal\_stretch .modal-dialog .modal-body { max-height: calc(100vh - 200px); overflow: auto; flex: 1; } @media (min-width: 768px) { .modal .modal-dialog { width: 700px; } } @media (min-width: 768px) { select.form-control { margin-left: 12px; margin-right: 12px; } } /*! * * IPython auth * */ .center-nav { display: inline-block; margin-bottom: -4px; } /*! * * IPython tree view * */ /* We need an invisible input field on top of the sentense*/ /* "Drag file onto the list ..." */ .alternate\_upload { background-color: none; display: inline; } .alternate\_upload.form { padding: 0; margin: 0; } .alternate\_upload input.fileinput { text-align: center; vertical-align: middle; display: inline; opacity: 0; z-index: 2; width: 12ex; margin-right: -12ex; } .alternate\_upload .btn-upload { height: 22px; } /** * Primary styles * * Author: Jupyter Development Team */ \[dir="rtl"\] #tabs li { float: right; } ul#tabs { margin-bottom: 4px; } \[dir="rtl"\] ul#tabs { margin-right: 0px; } ul#tabs a { padding-top: 6px; padding-bottom: 4px; } ul.breadcrumb a:focus, ul.breadcrumb a:hover { text-decoration: none; } ul.breadcrumb i.icon-home { font-size: 16px; margin-right: 4px; } ul.breadcrumb span { color: #5e5e5e; } .list\_toolbar { padding: 4px 0 4px 0; vertical-align: middle; } .list\_toolbar .tree-buttons { padding-top: 1px; } \[dir="rtl"\] .list\_toolbar .tree-buttons { float: left !important; } \[dir="rtl"\] .list\_toolbar .pull-right { padding-top: 1px; float: left !important; } \[dir="rtl"\] .list\_toolbar .pull-left { float: right !important; } .dynamic-buttons { padding-top: 3px; display: inline-block; } .list\_toolbar \[class*="span"\] { min-height: 24px; } .list\_header { font-weight: bold; background-color: #EEE; } .list\_placeholder { font-weight: bold; padding-top: 4px; padding-bottom: 4px; padding-left: 7px; padding-right: 7px; } .list\_container { margin-top: 4px; margin-bottom: 20px; border: 1px solid #ddd; border-radius: 2px; } .list\_container > div { border-bottom: 1px solid #ddd; } .list\_container > div:hover .list-item { background-color: red; } .list\_container > div:last-child { border: none; } .list\_item:hover .list\_item { background-color: #ddd; } .list\_item a { text-decoration: none; } .list\_item:hover { background-color: #fafafa; } .list\_header > div, .list\_item > div { padding-top: 4px; padding-bottom: 4px; padding-left: 7px; padding-right: 7px; line-height: 22px; } .list\_header > div input, .list\_item > div input { margin-right: 7px; margin-left: 14px; vertical-align: baseline; line-height: 22px; position: relative; top: -1px; } .list\_header > div .item\_link, .list\_item > div .item\_link { margin-left: -1px; vertical-align: baseline; line-height: 22px; } .new-file input\[type=checkbox\] { visibility: hidden; } .item\_name { line-height: 22px; height: 24px; } .item\_icon { font-size: 14px; color: #5e5e5e; margin-right: 7px; margin-left: 7px; line-height: 22px; vertical-align: baseline; } .item\_buttons { line-height: 1em; margin-left: -5px; } .item\_buttons .btn, .item\_buttons .btn-group, .item\_buttons .input-group { float: left; } .item\_buttons > .btn, .item\_buttons > .btn-group, .item\_buttons > .input-group { margin-left: 5px; } .item\_buttons .btn { min-width: 13ex; } .item\_buttons .running-indicator { padding-top: 4px; color: #5cb85c; } .item\_buttons .kernel-name { padding-top: 4px; color: #5bc0de; margin-right: 7px; float: left; } .toolbar\_info { height: 24px; line-height: 24px; } .list\_item input:not(\[type=checkbox\]) { padding-top: 3px; padding-bottom: 3px; height: 22px; line-height: 14px; margin: 0px; } .highlight\_text { color: blue; } #project\_name { display: inline-block; padding-left: 7px; margin-left: -2px; } #project\_name > .breadcrumb { padding: 0px; margin-bottom: 0px; background-color: transparent; font-weight: bold; } #tree-selector { padding-right: 0px; } \[dir="rtl"\] #tree-selector a { float: right; } #button-select-all { min-width: 50px; } #select-all { margin-left: 7px; margin-right: 2px; } .menu\_icon { margin-right: 2px; } .tab-content .row { margin-left: 0px; margin-right: 0px; } .folder\_icon:before { display: inline-block; font: normal normal normal 14px/1 FontAwesome; font-size: inherit; text-rendering: auto; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; content: "\\f114"; } .folder\_icon:before.pull-left { margin-right: .3em; } .folder\_icon:before.pull-right { margin-left: .3em; } .notebook\_icon:before { display: inline-block; font: normal normal normal 14px/1 FontAwesome; font-size: inherit; text-rendering: auto; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; content: "\\f02d"; position: relative; top: -1px; } .notebook\_icon:before.pull-left { margin-right: .3em; } .notebook\_icon:before.pull-right { margin-left: .3em; } .running\_notebook\_icon:before { display: inline-block; font: normal normal normal 14px/1 FontAwesome; font-size: inherit; text-rendering: auto; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; content: "\\f02d"; position: relative; top: -1px; color: #5cb85c; } .running\_notebook\_icon:before.pull-left { margin-right: .3em; } .running\_notebook\_icon:before.pull-right { margin-left: .3em; } .file\_icon:before { display: inline-block; font: normal normal normal 14px/1 FontAwesome; font-size: inherit; text-rendering: auto; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; content: "\\f016"; position: relative; top: -2px; } .file\_icon:before.pull-left { margin-right: .3em; } .file\_icon:before.pull-right { margin-left: .3em; } #notebook\_toolbar .pull-right { padding-top: 0px; margin-right: -1px; } ul#new-menu { left: auto; right: 0; } \[dir="rtl"\] #new-menu { text-align: right; } .kernel-menu-icon { padding-right: 12px; width: 24px; content: "\\f096"; } .kernel-menu-icon:before { content: "\\f096"; } .kernel-menu-icon-current:before { content: "\\f00c"; } #tab\_content { padding-top: 20px; } #running .panel-group .panel { margin-top: 3px; margin-bottom: 1em; } #running .panel-group .panel .panel-heading { background-color: #EEE; padding-top: 4px; padding-bottom: 4px; padding-left: 7px; padding-right: 7px; line-height: 22px; } #running .panel-group .panel .panel-heading a:focus, #running .panel-group .panel .panel-heading a:hover { text-decoration: none; } #running .panel-group .panel .panel-body { padding: 0px; } #running .panel-group .panel .panel-body .list\_container { margin-top: 0px; margin-bottom: 0px; border: 0px; border-radius: 0px; } #running .panel-group .panel .panel-body .list\_container .list\_item { border-bottom: 1px solid #ddd; } #running .panel-group .panel .panel-body .list\_container .list\_item:last-child { border-bottom: 0px; } \[dir="rtl"\] #running .col-sm-8 { float: right !important; } .delete-button { display: none; } .duplicate-button { display: none; } .rename-button { display: none; } .shutdown-button { display: none; } .dynamic-instructions { display: inline-block; padding-top: 4px; } /*! * * IPython text editor webapp * */ .selected-keymap i.fa { padding: 0px 5px; } .selected-keymap i.fa:before { content: "\\f00c"; } #mode-menu { overflow: auto; max-height: 20em; } .edit\_app #header { -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2); box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2); } .edit\_app #menubar .navbar { /* Use a negative 1 bottom margin, so the border overlaps the border of the header */ margin-bottom: -1px; } .dirty-indicator { display: inline-block; font: normal normal normal 14px/1 FontAwesome; font-size: inherit; text-rendering: auto; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; width: 20px; } .dirty-indicator.pull-left { margin-right: .3em; } .dirty-indicator.pull-right { margin-left: .3em; } .dirty-indicator-dirty { display: inline-block; font: normal normal normal 14px/1 FontAwesome; font-size: inherit; text-rendering: auto; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; width: 20px; } .dirty-indicator-dirty.pull-left { margin-right: .3em; } .dirty-indicator-dirty.pull-right { margin-left: .3em; } .dirty-indicator-clean { display: inline-block; font: normal normal normal 14px/1 FontAwesome; font-size: inherit; text-rendering: auto; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; width: 20px; } .dirty-indicator-clean.pull-left { margin-right: .3em; } .dirty-indicator-clean.pull-right { margin-left: .3em; } .dirty-indicator-clean:before { display: inline-block; font: normal normal normal 14px/1 FontAwesome; font-size: inherit; text-rendering: auto; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; content: "\\f00c"; } .dirty-indicator-clean:before.pull-left { margin-right: .3em; } .dirty-indicator-clean:before.pull-right { margin-left: .3em; } #filename { font-size: 16pt; display: table; padding: 0px 5px; } #current-mode { padding-left: 5px; padding-right: 5px; } #texteditor-backdrop { padding-top: 20px; padding-bottom: 20px; } @media not print { #texteditor-backdrop { background-color: #EEE; } } @media print { #texteditor-backdrop #texteditor-container .CodeMirror-gutter, #texteditor-backdrop #texteditor-container .CodeMirror-gutters { background-color: #fff; } } @media not print { #texteditor-backdrop #texteditor-container .CodeMirror-gutter, #texteditor-backdrop #texteditor-container .CodeMirror-gutters { background-color: #fff; } } @media not print { #texteditor-backdrop #texteditor-container { padding: 0px; background-color: #fff; -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2); box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2); } } /*! * * IPython notebook * */ /* CSS font colors for translated ANSI colors. */ .ansibold { font-weight: bold; } /* use dark versions for foreground, to improve visibility */ .ansiblack { color: black; } .ansired { color: darkred; } .ansigreen { color: darkgreen; } .ansiyellow { color: #c4a000; } .ansiblue { color: darkblue; } .ansipurple { color: darkviolet; } .ansicyan { color: steelblue; } .ansigray { color: gray; } /* and light for background, for the same reason */ .ansibgblack { background-color: black; } .ansibgred { background-color: red; } .ansibggreen { background-color: green; } .ansibgyellow { background-color: yellow; } .ansibgblue { background-color: blue; } .ansibgpurple { background-color: magenta; } .ansibgcyan { background-color: cyan; } .ansibggray { background-color: gray; } div.cell { /* Old browsers */ display: -webkit-box; -webkit-box-orient: vertical; -webkit-box-align: stretch; display: -moz-box; -moz-box-orient: vertical; -moz-box-align: stretch; display: box; box-orient: vertical; box-align: stretch; /* Modern browsers */ display: flex; flex-direction: column; align-items: stretch; border-radius: 2px; box-sizing: border-box; -moz-box-sizing: border-box; -webkit-box-sizing: border-box; border-width: 1px; border-style: solid; border-color: transparent; width: 100%; padding: 5px; /* This acts as a spacer between cells, that is outside the border */ margin: 0px; outline: none; border-left-width: 1px; padding-left: 5px; background: linear-gradient(to right, transparent -40px, transparent 1px, transparent 1px, transparent 100%); } div.cell.jupyter-soft-selected { border-left-color: #90CAF9; border-left-color: #E3F2FD; border-left-width: 1px; padding-left: 5px; border-right-color: #E3F2FD; border-right-width: 1px; background: #E3F2FD; } @media print { div.cell.jupyter-soft-selected { border-color: transparent; } } div.cell.selected { border-color: #ababab; border-left-width: 0px; padding-left: 6px; background: linear-gradient(to right, #42A5F5 -40px, #42A5F5 5px, transparent 5px, transparent 100%); } @media print { div.cell.selected { border-color: transparent; } } div.cell.selected.jupyter-soft-selected { border-left-width: 0; padding-left: 6px; background: linear-gradient(to right, #42A5F5 -40px, #42A5F5 7px, #E3F2FD 7px, #E3F2FD 100%); } .edit\_mode div.cell.selected { border-color: #66BB6A; border-left-width: 0px; padding-left: 6px; background: linear-gradient(to right, #66BB6A -40px, #66BB6A 5px, transparent 5px, transparent 100%); } @media print { .edit\_mode div.cell.selected { border-color: transparent; } } .prompt { /* This needs to be wide enough for 3 digit prompt numbers: In\[100\]: */ min-width: 14ex; /* This padding is tuned to match the padding on the CodeMirror editor. */ padding: 0.4em; margin: 0px; font-family: monospace; text-align: right; /* This has to match that of the the CodeMirror class line-height below */ line-height: 1.21429em; /* Don't highlight prompt number selection */ -webkit-touch-callout: none; -webkit-user-select: none; -khtml-user-select: none; -moz-user-select: none; -ms-user-select: none; user-select: none; /* Use default cursor */ cursor: default; } @media (max-width: 540px) { .prompt { text-align: left; } } div.inner\_cell { min-width: 0; /* Old browsers */ display: -webkit-box; -webkit-box-orient: vertical; -webkit-box-align: stretch; display: -moz-box; -moz-box-orient: vertical; -moz-box-align: stretch; display: box; box-orient: vertical; box-align: stretch; /* Modern browsers */ display: flex; flex-direction: column; align-items: stretch; /* Old browsers */ -webkit-box-flex: 1; -moz-box-flex: 1; box-flex: 1; /* Modern browsers */ flex: 1; } /* input\_area and input\_prompt must match in top border and margin for alignment */ div.input\_area { border: 1px solid #cfcfcf; border-radius: 2px; background: #f7f7f7; line-height: 1.21429em; } /* This is needed so that empty prompt areas can collapse to zero height when there is no content in the output\_subarea and the prompt. The main purpose of this is to make sure that empty JavaScript output\_subareas have no height. */ div.prompt:empty { padding-top: 0; padding-bottom: 0; } div.unrecognized\_cell { padding: 5px 5px 5px 0px; /* Old browsers */ display: -webkit-box; -webkit-box-orient: horizontal; -webkit-box-align: stretch; display: -moz-box; -moz-box-orient: horizontal; -moz-box-align: stretch; display: box; box-orient: horizontal; box-align: stretch; /* Modern browsers */ display: flex; flex-direction: row; align-items: stretch; } div.unrecognized\_cell .inner\_cell { border-radius: 2px; padding: 5px; font-weight: bold; color: red; border: 1px solid #cfcfcf; background: #eaeaea; } div.unrecognized\_cell .inner\_cell a { color: inherit; text-decoration: none; } div.unrecognized\_cell .inner\_cell a:hover { color: inherit; text-decoration: none; } @media (max-width: 540px) { div.unrecognized\_cell > div.prompt { display: none; } } div.code\_cell { /* avoid page breaking on code cells when printing */ } @media print { div.code\_cell { page-break-inside: avoid; } } /* any special styling for code cells that are currently running goes here */ div.input { page-break-inside: avoid; /* Old browsers */ display: -webkit-box; -webkit-box-orient: horizontal; -webkit-box-align: stretch; display: -moz-box; -moz-box-orient: horizontal; -moz-box-align: stretch; display: box; box-orient: horizontal; box-align: stretch; /* Modern browsers */ display: flex; flex-direction: row; align-items: stretch; } @media (max-width: 540px) { div.input { /* Old browsers */ display: -webkit-box; -webkit-box-orient: vertical; -webkit-box-align: stretch; display: -moz-box; -moz-box-orient: vertical; -moz-box-align: stretch; display: box; box-orient: vertical; box-align: stretch; /* Modern browsers */ display: flex; flex-direction: column; align-items: stretch; } } /* input\_area and input\_prompt must match in top border and margin for alignment */ div.input\_prompt { color: #303F9F; border-top: 1px solid transparent; } div.input\_area > div.highlight { margin: 0.4em; border: none; padding: 0px; background-color: transparent; } div.input\_area > div.highlight > pre { margin: 0px; border: none; padding: 0px; background-color: transparent; } /* The following gets added to the <head> if it is detected that the user has a * monospace font with inconsistent normal/bold/italic height. See * notebookmain.js. Such fonts will have keywords vertically offset with * respect to the rest of the text. The user should select a better font. * See: https://github.com/ipython/ipython/issues/1503 * * .CodeMirror span { * vertical-align: bottom; * } */ .CodeMirror { line-height: 1.21429em; /* Changed from 1em to our global default */ font-size: 14px; height: auto; /* Changed to auto to autogrow */ background: none; /* Changed from white to allow our bg to show through */ } .CodeMirror-scroll { /* The CodeMirror docs are a bit fuzzy on if overflow-y should be hidden or visible.*/ /* We have found that if it is visible, vertical scrollbars appear with font size changes.*/ overflow-y: hidden; overflow-x: auto; } .CodeMirror-lines { /* In CM2, this used to be 0.4em, but in CM3 it went to 4px. We need the em value because */ /* we have set a different line-height and want this to scale with that. */ padding: 0.4em; } .CodeMirror-linenumber { padding: 0 8px 0 4px; } .CodeMirror-gutters { border-bottom-left-radius: 2px; border-top-left-radius: 2px; } .CodeMirror pre { /* In CM3 this went to 4px from 0 in CM2. We need the 0 value because of how we size */ /* .CodeMirror-lines */ padding: 0; border: 0; border-radius: 0; } /* Original style from softwaremaniacs.org (c) Ivan Sagalaev <Maniac@SoftwareManiacs.Org> Adapted from GitHub theme */ .highlight-base { color: #000; } .highlight-variable { color: #000; } .highlight-variable-2 { color: #1a1a1a; } .highlight-variable-3 { color: #333333; } .highlight-string { color: #BA2121; } .highlight-comment { color: #408080; font-style: italic; } .highlight-number { color: #080; } .highlight-atom { color: #88F; } .highlight-keyword { color: #008000; font-weight: bold; } .highlight-builtin { color: #008000; } .highlight-error { color: #f00; } .highlight-operator { color: #AA22FF; font-weight: bold; } .highlight-meta { color: #AA22FF; } /* previously not defined, copying from default codemirror */ .highlight-def { color: #00f; } .highlight-string-2 { color: #f50; } .highlight-qualifier { color: #555; } .highlight-bracket { color: #997; } .highlight-tag { color: #170; } .highlight-attribute { color: #00c; } .highlight-header { color: blue; } .highlight-quote { color: #090; } .highlight-link { color: #00c; } /* apply the same style to codemirror */ .cm-s-ipython span.cm-keyword { color: #008000; font-weight: bold; } .cm-s-ipython span.cm-atom { color: #88F; } .cm-s-ipython span.cm-number { color: #080; } .cm-s-ipython span.cm-def { color: #00f; } .cm-s-ipython span.cm-variable { color: #000; } .cm-s-ipython span.cm-operator { color: #AA22FF; font-weight: bold; } .cm-s-ipython span.cm-variable-2 { color: #1a1a1a; } .cm-s-ipython span.cm-variable-3 { color: #333333; } .cm-s-ipython span.cm-comment { color: #408080; font-style: italic; } .cm-s-ipython span.cm-string { color: #BA2121; } .cm-s-ipython span.cm-string-2 { color: #f50; } .cm-s-ipython span.cm-meta { color: #AA22FF; } .cm-s-ipython span.cm-qualifier { color: #555; } .cm-s-ipython span.cm-builtin { color: #008000; } .cm-s-ipython span.cm-bracket { color: #997; } .cm-s-ipython span.cm-tag { color: #170; } .cm-s-ipython span.cm-attribute { color: #00c; } .cm-s-ipython span.cm-header { color: blue; } .cm-s-ipython span.cm-quote { color: #090; } .cm-s-ipython span.cm-link { color: #00c; } .cm-s-ipython span.cm-error { color: #f00; } .cm-s-ipython span.cm-tab { background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAMCAYAAAAkuj5RAAAAAXNSR0IArs4c6QAAAGFJREFUSMft1LsRQFAQheHPowAKoACx3IgEKtaEHujDjORSgWTH/ZOdnZOcM/sgk/kFFWY0qV8foQwS4MKBCS3qR6ixBJvElOobYAtivseIE120FaowJPN75GMu8j/LfMwNjh4HUpwg4LUAAAAASUVORK5CYII=); background-position: right; background-repeat: no-repeat; } div.output\_wrapper { /* this position must be relative to enable descendents to be absolute within it */ position: relative; /* Old browsers */ display: -webkit-box; -webkit-box-orient: vertical; -webkit-box-align: stretch; display: -moz-box; -moz-box-orient: vertical; -moz-box-align: stretch; display: box; box-orient: vertical; box-align: stretch; /* Modern browsers */ display: flex; flex-direction: column; align-items: stretch; z-index: 1; } /* class for the output area when it should be height-limited */ div.output\_scroll { /* ideally, this would be max-height, but FF barfs all over that */ height: 24em; /* FF needs this \*and the wrapper\* to specify full width, or it will shrinkwrap */ width: 100%; overflow: auto; border-radius: 2px; -webkit-box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8); box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8); display: block; } /* output div while it is collapsed */ div.output\_collapsed { margin: 0px; padding: 0px; /* Old browsers */ display: -webkit-box; -webkit-box-orient: vertical; -webkit-box-align: stretch; display: -moz-box; -moz-box-orient: vertical; -moz-box-align: stretch; display: box; box-orient: vertical; box-align: stretch; /* Modern browsers */ display: flex; flex-direction: column; align-items: stretch; } div.out\_prompt\_overlay { height: 100%; padding: 0px 0.4em; position: absolute; border-radius: 2px; } div.out\_prompt\_overlay:hover { /* use inner shadow to get border that is computed the same on WebKit/FF */ -webkit-box-shadow: inset 0 0 1px #000; box-shadow: inset 0 0 1px #000; background: rgba(240, 240, 240, 0.5); } div.output\_prompt { color: #D84315; } /* This class is the outer container of all output sections. */ div.output\_area { padding: 0px; page-break-inside: avoid; /* Old browsers */ display: -webkit-box; -webkit-box-orient: horizontal; -webkit-box-align: stretch; display: -moz-box; -moz-box-orient: horizontal; -moz-box-align: stretch; display: box; box-orient: horizontal; box-align: stretch; /* Modern browsers */ display: flex; flex-direction: row; align-items: stretch; } div.output\_area .MathJax\_Display { text-align: left !important; } div.output\_area .rendered\_html table { margin-left: 0; margin-right: 0; } div.output\_area .rendered\_html img { margin-left: 0; margin-right: 0; } div.output\_area img, div.output\_area svg { max-width: 100%; height: auto; } div.output\_area img.unconfined, div.output\_area svg.unconfined { max-width: none; } /* This is needed to protect the pre formating from global settings such as that of bootstrap */ .output { /* Old browsers */ display: -webkit-box; -webkit-box-orient: vertical; -webkit-box-align: stretch; display: -moz-box; -moz-box-orient: vertical; -moz-box-align: stretch; display: box; box-orient: vertical; box-align: stretch; /* Modern browsers */ display: flex; flex-direction: column; align-items: stretch; } @media (max-width: 540px) { div.output\_area { /* Old browsers */ display: -webkit-box; -webkit-box-orient: vertical; -webkit-box-align: stretch; display: -moz-box; -moz-box-orient: vertical; -moz-box-align: stretch; display: box; box-orient: vertical; box-align: stretch; /* Modern browsers */ display: flex; flex-direction: column; align-items: stretch; } } div.output\_area pre { margin: 0; padding: 0; border: 0; vertical-align: baseline; color: black; background-color: transparent; border-radius: 0; } /* This class is for the output subarea inside the output\_area and after the prompt div. */ div.output\_subarea { overflow-x: auto; padding: 0.4em; /* Old browsers */ -webkit-box-flex: 1; -moz-box-flex: 1; box-flex: 1; /* Modern browsers */ flex: 1; max-width: calc(100% - 14ex); } div.output\_scroll div.output\_subarea { overflow-x: visible; } /* The rest of the output_* classes are for special styling of the different output types */ /* all text output has this class: */ div.output\_text { text-align: left; color: #000; /* This has to match that of the the CodeMirror class line-height below */ line-height: 1.21429em; } /* stdout/stderr are 'text' as well as 'stream', but execute\_result/error are \*not\* streams */ div.output\_stderr { background: #fdd; /* very light red background for stderr */ } div.output\_latex { text-align: left; } /* Empty output\_javascript divs should have no height */ div.output\_javascript:empty { padding: 0; } .js-error { color: darkred; } /* raw\_input styles */ div.raw\_input\_container { line-height: 1.21429em; padding-top: 5px; } pre.raw\_input\_prompt { /* nothing needed here. */ } input.raw\_input { font-family: monospace; font-size: inherit; color: inherit; width: auto; /* make sure input baseline aligns with prompt */ vertical-align: baseline; /* padding + margin = 0.5em between prompt and cursor */ padding: 0em 0.25em; margin: 0em 0.25em; } input.raw\_input:focus { box-shadow: none; } p.p-space { margin-bottom: 10px; } div.output\_unrecognized { padding: 5px; font-weight: bold; color: red; } div.output\_unrecognized a { color: inherit; text-decoration: none; } div.output\_unrecognized a:hover { color: inherit; text-decoration: none; } .rendered\_html { color: #000; /* any extras will just be numbers: */ } .rendered\_html em { font-style: italic; } .rendered\_html strong { font-weight: bold; } .rendered\_html u { text-decoration: underline; } .rendered\_html :link { text-decoration: underline; } .rendered\_html :visited { text-decoration: underline; } .rendered\_html h1 { font-size: 185.7%; margin: 1.08em 0 0 0; font-weight: bold; line-height: 1.0; } .rendered\_html h2 { font-size: 157.1%; margin: 1.27em 0 0 0; font-weight: bold; line-height: 1.0; } .rendered\_html h3 { font-size: 128.6%; margin: 1.55em 0 0 0; font-weight: bold; line-height: 1.0; } .rendered\_html h4 { font-size: 100%; margin: 2em 0 0 0; font-weight: bold; line-height: 1.0; } .rendered\_html h5 { font-size: 100%; margin: 2em 0 0 0; font-weight: bold; line-height: 1.0; font-style: italic; } .rendered\_html h6 { font-size: 100%; margin: 2em 0 0 0; font-weight: bold; line-height: 1.0; font-style: italic; } .rendered\_html h1:first-child { margin-top: 0.538em; } .rendered\_html h2:first-child { margin-top: 0.636em; } .rendered\_html h3:first-child { margin-top: 0.777em; } .rendered\_html h4:first-child { margin-top: 1em; } .rendered\_html h5:first-child { margin-top: 1em; } .rendered\_html h6:first-child { margin-top: 1em; } .rendered\_html ul { list-style: disc; margin: 0em 2em; padding-left: 0px; } .rendered\_html ul ul { list-style: square; margin: 0em 2em; } .rendered\_html ul ul ul { list-style: circle; margin: 0em 2em; } .rendered\_html ol { list-style: decimal; margin: 0em 2em; padding-left: 0px; } .rendered\_html ol ol { list-style: upper-alpha; margin: 0em 2em; } .rendered\_html ol ol ol { list-style: lower-alpha; margin: 0em 2em; } .rendered\_html ol ol ol ol { list-style: lower-roman; margin: 0em 2em; } .rendered\_html ol ol ol ol ol { list-style: decimal; margin: 0em 2em; } .rendered\_html * + ul { margin-top: 1em; } .rendered\_html * + ol { margin-top: 1em; } .rendered\_html hr { color: black; background-color: black; } .rendered\_html pre { margin: 1em 2em; } .rendered\_html pre, .rendered\_html code { border: 0; background-color: #fff; color: #000; font-size: 100%; padding: 0px; } .rendered\_html blockquote { margin: 1em 2em; } .rendered\_html table { margin-left: auto; margin-right: auto; border: 1px solid black; border-collapse: collapse; } .rendered\_html tr, .rendered\_html th, .rendered\_html td { border: 1px solid black; border-collapse: collapse; margin: 1em 2em; } .rendered\_html td, .rendered\_html th { text-align: left; vertical-align: middle; padding: 4px; } .rendered\_html th { font-weight: bold; } .rendered\_html * + table { margin-top: 1em; } .rendered\_html p { text-align: left; } .rendered\_html * + p { margin-top: 1em; } .rendered\_html img { display: block; margin-left: auto; margin-right: auto; } .rendered\_html * + img { margin-top: 1em; } .rendered\_html img, .rendered\_html svg { max-width: 100%; height: auto; } .rendered\_html img.unconfined, .rendered\_html svg.unconfined { max-width: none; } div.text\_cell { /* Old browsers */ display: -webkit-box; -webkit-box-orient: horizontal; -webkit-box-align: stretch; display: -moz-box; -moz-box-orient: horizontal; -moz-box-align: stretch; display: box; box-orient: horizontal; box-align: stretch; /* Modern browsers */ display: flex; flex-direction: row; align-items: stretch; } @media (max-width: 540px) { div.text\_cell > div.prompt { display: none; } } div.text\_cell\_render { /\*font-family: "Helvetica Neue", Arial, Helvetica, Geneva, sans-serif;\*/ outline: none; resize: none; width: inherit; border-style: none; padding: 0.5em 0.5em 0.5em 0.4em; color: #000; box-sizing: border-box; -moz-box-sizing: border-box; -webkit-box-sizing: border-box; } a.anchor-link:link { text-decoration: none; padding: 0px 20px; visibility: hidden; } h1:hover .anchor-link, h2:hover .anchor-link, h3:hover .anchor-link, h4:hover .anchor-link, h5:hover .anchor-link, h6:hover .anchor-link { visibility: visible; } .text\_cell.rendered .input\_area { display: none; } .text\_cell.rendered .rendered\_html { overflow-x: auto; overflow-y: hidden; } .text\_cell.unrendered .text\_cell\_render { display: none; } .cm-header-1, .cm-header-2, .cm-header-3, .cm-header-4, .cm-header-5, .cm-header-6 { font-weight: bold; font-family: "Helvetica Neue", Helvetica, Arial, sans-serif; } .cm-header-1 { font-size: 185.7%; } .cm-header-2 { font-size: 157.1%; } .cm-header-3 { font-size: 128.6%; } .cm-header-4 { font-size: 110%; } .cm-header-5 { font-size: 100%; font-style: italic; } .cm-header-6 { font-size: 100%; font-style: italic; } /*! * * IPython notebook webapp * */ @media (max-width: 767px) { .notebook\_app { padding-left: 0px; padding-right: 0px; } } #ipython-main-app { box-sizing: border-box; -moz-box-sizing: border-box; -webkit-box-sizing: border-box; height: 100%; } div#notebook\_panel { margin: 0px; padding: 0px; box-sizing: border-box; -moz-box-sizing: border-box; -webkit-box-sizing: border-box; height: 100%; } div#notebook { font-size: 14px; line-height: 20px; overflow-y: hidden; overflow-x: auto; width: 100%; /* This spaces the page away from the edge of the notebook area */ padding-top: 20px; margin: 0px; outline: none; box-sizing: border-box; -moz-box-sizing: border-box; -webkit-box-sizing: border-box; min-height: 100%; } @media not print { #notebook-container { padding: 15px; background-color: #fff; min-height: 0; -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2); box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2); } } @media print { #notebook-container { width: 100%; } } div.ui-widget-content { border: 1px solid #ababab; outline: none; } pre.dialog { background-color: #f7f7f7; border: 1px solid #ddd; border-radius: 2px; padding: 0.4em; padding-left: 2em; } p.dialog { padding: 0.2em; } /* Word-wrap output correctly. This is the CSS3 spelling, though Firefox seems to not honor it correctly. Webkit browsers (Chrome, rekonq, Safari) do. */ pre, code, kbd, samp { white-space: pre-wrap; } #fonttest { font-family: monospace; } p { margin-bottom: 0; } .end\_space { min-height: 100px; transition: height .2s ease; } .notebook\_app > #header { -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2); box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2); } @media not print { .notebook\_app { background-color: #EEE; } } kbd { border-style: solid; border-width: 1px; box-shadow: none; margin: 2px; padding-left: 2px; padding-right: 2px; padding-top: 1px; padding-bottom: 1px; } /* CSS for the cell toolbar */ .celltoolbar { border: thin solid #CFCFCF; border-bottom: none; background: #EEE; border-radius: 2px 2px 0px 0px; width: 100%; height: 29px; padding-right: 4px; /* Old browsers */ display: -webkit-box; -webkit-box-orient: horizontal; -webkit-box-align: stretch; display: -moz-box; -moz-box-orient: horizontal; -moz-box-align: stretch; display: box; box-orient: horizontal; box-align: stretch; /* Modern browsers */ display: flex; flex-direction: row; align-items: stretch; /* Old browsers */ -webkit-box-pack: end; -moz-box-pack: end; box-pack: end; /* Modern browsers */ justify-content: flex-end; display: -webkit-flex; } @media print { .celltoolbar { display: none; } } .ctb\_hideshow { display: none; vertical-align: bottom; } /* ctb\_show is added to the ctb\_hideshow div to show the cell toolbar. Cell toolbars are only shown when the ctb\_global\_show class is also set. */ .ctb\_global\_show .ctb\_show.ctb\_hideshow { display: block; } .ctb\_global\_show .ctb\_show + .input\_area, .ctb\_global\_show .ctb\_show + div.text\_cell\_input, .ctb\_global\_show .ctb\_show ~ div.text\_cell\_render { border-top-right-radius: 0px; border-top-left-radius: 0px; } .ctb\_global\_show .ctb\_show ~ div.text\_cell\_render { border: 1px solid #cfcfcf; } .celltoolbar { font-size: 87%; padding-top: 3px; } .celltoolbar select { display: block; width: 100%; height: 32px; padding: 6px 12px; font-size: 13px; line-height: 1.42857143; color: #555555; background-color: #fff; background-image: none; border: 1px solid #ccc; border-radius: 2px; -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075); box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075); -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s; -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s; transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s; height: 30px; padding: 5px 10px; font-size: 12px; line-height: 1.5; border-radius: 1px; width: inherit; font-size: inherit; height: 22px; padding: 0px; display: inline-block; } .celltoolbar select:focus { border-color: #66afe9; outline: 0; -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6); box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6); } .celltoolbar select::-moz-placeholder { color: #999; opacity: 1; } .celltoolbar select:-ms-input-placeholder { color: #999; } .celltoolbar select::-webkit-input-placeholder { color: #999; } .celltoolbar select::-ms-expand { border: 0; background-color: transparent; } .celltoolbar select\[disabled\], .celltoolbar select\[readonly\], fieldset\[disabled\] .celltoolbar select { background-color: #eeeeee; opacity: 1; } .celltoolbar select\[disabled\], fieldset\[disabled\] .celltoolbar select { cursor: not-allowed; } textarea.celltoolbar select { height: auto; } select.celltoolbar select { height: 30px; line-height: 30px; } textarea.celltoolbar select, select\[multiple\].celltoolbar select { height: auto; } .celltoolbar label { margin-left: 5px; margin-right: 5px; } .completions { position: absolute; z-index: 110; overflow: hidden; border: 1px solid #ababab; border-radius: 2px; -webkit-box-shadow: 0px 6px 10px -1px #adadad; box-shadow: 0px 6px 10px -1px #adadad; line-height: 1; } .completions select { background: white; outline: none; border: none; padding: 0px; margin: 0px; overflow: auto; font-family: monospace; font-size: 110%; color: #000; width: auto; } .completions select option.context { color: #286090; } #kernel\_logo\_widget { float: right !important; float: right; } #kernel\_logo\_widget .current\_kernel\_logo { display: none; margin-top: -1px; margin-bottom: -1px; width: 32px; height: 32px; } #menubar { box-sizing: border-box; -moz-box-sizing: border-box; -webkit-box-sizing: border-box; margin-top: 1px; } #menubar .navbar { border-top: 1px; border-radius: 0px 0px 2px 2px; margin-bottom: 0px; } #menubar .navbar-toggle { float: left; padding-top: 7px; padding-bottom: 7px; border: none; } #menubar .navbar-collapse { clear: left; } .nav-wrapper { border-bottom: 1px solid #e7e7e7; } i.menu-icon { padding-top: 4px; } ul#help\_menu li a { overflow: hidden; padding-right: 2.2em; } ul#help\_menu li a i { margin-right: -1.2em; } .dropdown-submenu { position: relative; } .dropdown-submenu > .dropdown-menu { top: 0; left: 100%; margin-top: -6px; margin-left: -1px; } .dropdown-submenu:hover > .dropdown-menu { display: block; } .dropdown-submenu > a:after { display: inline-block; font: normal normal normal 14px/1 FontAwesome; font-size: inherit; text-rendering: auto; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; display: block; content: "\\f0da"; float: right; color: #333333; margin-top: 2px; margin-right: -10px; } .dropdown-submenu > a:after.pull-left { margin-right: .3em; } .dropdown-submenu > a:after.pull-right { margin-left: .3em; } .dropdown-submenu:hover > a:after { color: #262626; } .dropdown-submenu.pull-left { float: none; } .dropdown-submenu.pull-left > .dropdown-menu { left: -100%; margin-left: 10px; } #notification\_area { float: right !important; float: right; z-index: 10; } .indicator\_area { float: right !important; float: right; color: #777; margin-left: 5px; margin-right: 5px; width: 11px; z-index: 10; text-align: center; width: auto; } #kernel\_indicator { float: right !important; float: right; color: #777; margin-left: 5px; margin-right: 5px; width: 11px; z-index: 10; text-align: center; width: auto; border-left: 1px solid; } #kernel\_indicator .kernel\_indicator\_name { padding-left: 5px; padding-right: 5px; } #modal\_indicator { float: right !important; float: right; color: #777; margin-left: 5px; margin-right: 5px; width: 11px; z-index: 10; text-align: center; width: auto; } #readonly-indicator { float: right !important; float: right; color: #777; margin-left: 5px; margin-right: 5px; width: 11px; z-index: 10; text-align: center; width: auto; margin-top: 2px; margin-bottom: 0px; margin-left: 0px; margin-right: 0px; display: none; } .modal\_indicator:before { width: 1.28571429em; text-align: center; } .edit\_mode .modal\_indicator:before { display: inline-block; font: normal normal normal 14px/1 FontAwesome; font-size: inherit; text-rendering: auto; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; content: "\\f040"; } .edit\_mode .modal\_indicator:before.pull-left { margin-right: .3em; } .edit\_mode .modal\_indicator:before.pull-right { margin-left: .3em; } .command\_mode .modal\_indicator:before { display: inline-block; font: normal normal normal 14px/1 FontAwesome; font-size: inherit; text-rendering: auto; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; content: ' '; } .command\_mode .modal\_indicator:before.pull-left { margin-right: .3em; } .command\_mode .modal\_indicator:before.pull-right { margin-left: .3em; } .kernel\_idle\_icon:before { display: inline-block; font: normal normal normal 14px/1 FontAwesome; font-size: inherit; text-rendering: auto; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; content: "\\f10c"; } .kernel\_idle\_icon:before.pull-left { margin-right: .3em; } .kernel\_idle\_icon:before.pull-right { margin-left: .3em; } .kernel\_busy\_icon:before { display: inline-block; font: normal normal normal 14px/1 FontAwesome; font-size: inherit; text-rendering: auto; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; content: "\\f111"; } .kernel\_busy\_icon:before.pull-left { margin-right: .3em; } .kernel\_busy\_icon:before.pull-right { margin-left: .3em; } .kernel\_dead\_icon:before { display: inline-block; font: normal normal normal 14px/1 FontAwesome; font-size: inherit; text-rendering: auto; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; content: "\\f1e2"; } .kernel\_dead\_icon:before.pull-left { margin-right: .3em; } .kernel\_dead\_icon:before.pull-right { margin-left: .3em; } .kernel\_disconnected\_icon:before { display: inline-block; font: normal normal normal 14px/1 FontAwesome; font-size: inherit; text-rendering: auto; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; content: "\\f127"; } .kernel\_disconnected\_icon:before.pull-left { margin-right: .3em; } .kernel\_disconnected\_icon:before.pull-right { margin-left: .3em; } .notification\_widget { color: #777; z-index: 10; background: rgba(240, 240, 240, 0.5); margin-right: 4px; color: #333; background-color: #fff; border-color: #ccc; } .notification\_widget:focus, .notification\_widget.focus { color: #333; background-color: #e6e6e6; border-color: #8c8c8c; } .notification\_widget:hover { color: #333; background-color: #e6e6e6; border-color: #adadad; } .notification\_widget:active, .notification\_widget.active, .open > .dropdown-toggle.notification\_widget { color: #333; background-color: #e6e6e6; border-color: #adadad; } .notification\_widget:active:hover, .notification\_widget.active:hover, .open > .dropdown-toggle.notification\_widget:hover, .notification\_widget:active:focus, .notification\_widget.active:focus, .open > .dropdown-toggle.notification\_widget:focus, .notification\_widget:active.focus, .notification\_widget.active.focus, .open > .dropdown-toggle.notification\_widget.focus { color: #333; background-color: #d4d4d4; border-color: #8c8c8c; } .notification\_widget:active, .notification\_widget.active, .open > .dropdown-toggle.notification\_widget { background-image: none; } .notification\_widget.disabled:hover, .notification\_widget\[disabled\]:hover, fieldset\[disabled\] .notification\_widget:hover, .notification\_widget.disabled:focus, .notification\_widget\[disabled\]:focus, fieldset\[disabled\] .notification\_widget:focus, .notification\_widget.disabled.focus, .notification\_widget\[disabled\].focus, fieldset\[disabled\] .notification\_widget.focus { background-color: #fff; border-color: #ccc; } .notification\_widget .badge { color: #fff; background-color: #333; } .notification\_widget.warning { color: #fff; background-color: #f0ad4e; border-color: #eea236; } .notification\_widget.warning:focus, .notification\_widget.warning.focus { color: #fff; background-color: #ec971f; border-color: #985f0d; } .notification\_widget.warning:hover { color: #fff; background-color: #ec971f; border-color: #d58512; } .notification\_widget.warning:active, .notification\_widget.warning.active, .open > .dropdown-toggle.notification\_widget.warning { color: #fff; background-color: #ec971f; border-color: #d58512; } .notification\_widget.warning:active:hover, .notification\_widget.warning.active:hover, .open > .dropdown-toggle.notification\_widget.warning:hover, .notification\_widget.warning:active:focus, .notification\_widget.warning.active:focus, .open > .dropdown-toggle.notification\_widget.warning:focus, .notification\_widget.warning:active.focus, .notification\_widget.warning.active.focus, .open > .dropdown-toggle.notification\_widget.warning.focus { color: #fff; background-color: #d58512; border-color: #985f0d; } .notification\_widget.warning:active, .notification\_widget.warning.active, .open > .dropdown-toggle.notification\_widget.warning { background-image: none; } .notification\_widget.warning.disabled:hover, .notification\_widget.warning\[disabled\]:hover, fieldset\[disabled\] .notification\_widget.warning:hover, .notification\_widget.warning.disabled:focus, .notification\_widget.warning\[disabled\]:focus, fieldset\[disabled\] .notification\_widget.warning:focus, .notification\_widget.warning.disabled.focus, .notification\_widget.warning\[disabled\].focus, fieldset\[disabled\] .notification\_widget.warning.focus { background-color: #f0ad4e; border-color: #eea236; } .notification\_widget.warning .badge { color: #f0ad4e; background-color: #fff; } .notification\_widget.success { color: #fff; background-color: #5cb85c; border-color: #4cae4c; } .notification\_widget.success:focus, .notification\_widget.success.focus { color: #fff; background-color: #449d44; border-color: #255625; } .notification\_widget.success:hover { color: #fff; background-color: #449d44; border-color: #398439; } .notification\_widget.success:active, .notification\_widget.success.active, .open > .dropdown-toggle.notification\_widget.success { color: #fff; background-color: #449d44; border-color: #398439; } .notification\_widget.success:active:hover, .notification\_widget.success.active:hover, .open > .dropdown-toggle.notification\_widget.success:hover, .notification\_widget.success:active:focus, .notification\_widget.success.active:focus, .open > .dropdown-toggle.notification\_widget.success:focus, .notification\_widget.success:active.focus, .notification\_widget.success.active.focus, .open > .dropdown-toggle.notification\_widget.success.focus { color: #fff; background-color: #398439; border-color: #255625; } .notification\_widget.success:active, .notification\_widget.success.active, .open > .dropdown-toggle.notification\_widget.success { background-image: none; } .notification\_widget.success.disabled:hover, .notification\_widget.success\[disabled\]:hover, fieldset\[disabled\] .notification\_widget.success:hover, .notification\_widget.success.disabled:focus, .notification\_widget.success\[disabled\]:focus, fieldset\[disabled\] .notification\_widget.success:focus, .notification\_widget.success.disabled.focus, .notification\_widget.success\[disabled\].focus, fieldset\[disabled\] .notification\_widget.success.focus { background-color: #5cb85c; border-color: #4cae4c; } .notification\_widget.success .badge { color: #5cb85c; background-color: #fff; } .notification\_widget.info { color: #fff; background-color: #5bc0de; border-color: #46b8da; } .notification\_widget.info:focus, .notification\_widget.info.focus { color: #fff; background-color: #31b0d5; border-color: #1b6d85; } .notification\_widget.info:hover { color: #fff; background-color: #31b0d5; border-color: #269abc; } .notification\_widget.info:active, .notification\_widget.info.active, .open > .dropdown-toggle.notification\_widget.info { color: #fff; background-color: #31b0d5; border-color: #269abc; } .notification\_widget.info:active:hover, .notification\_widget.info.active:hover, .open > .dropdown-toggle.notification\_widget.info:hover, .notification\_widget.info:active:focus, .notification\_widget.info.active:focus, .open > .dropdown-toggle.notification\_widget.info:focus, .notification\_widget.info:active.focus, .notification\_widget.info.active.focus, .open > .dropdown-toggle.notification\_widget.info.focus { color: #fff; background-color: #269abc; border-color: #1b6d85; } .notification\_widget.info:active, .notification\_widget.info.active, .open > .dropdown-toggle.notification\_widget.info { background-image: none; } .notification\_widget.info.disabled:hover, .notification\_widget.info\[disabled\]:hover, fieldset\[disabled\] .notification\_widget.info:hover, .notification\_widget.info.disabled:focus, .notification\_widget.info\[disabled\]:focus, fieldset\[disabled\] .notification\_widget.info:focus, .notification\_widget.info.disabled.focus, .notification\_widget.info\[disabled\].focus, fieldset\[disabled\] .notification\_widget.info.focus { background-color: #5bc0de; border-color: #46b8da; } .notification\_widget.info .badge { color: #5bc0de; background-color: #fff; } .notification\_widget.danger { color: #fff; background-color: #d9534f; border-color: #d43f3a; } .notification\_widget.danger:focus, .notification\_widget.danger.focus { color: #fff; background-color: #c9302c; border-color: #761c19; } .notification\_widget.danger:hover { color: #fff; background-color: #c9302c; border-color: #ac2925; } .notification\_widget.danger:active, .notification\_widget.danger.active, .open > .dropdown-toggle.notification\_widget.danger { color: #fff; background-color: #c9302c; border-color: #ac2925; } .notification\_widget.danger:active:hover, .notification\_widget.danger.active:hover, .open > .dropdown-toggle.notification\_widget.danger:hover, .notification\_widget.danger:active:focus, .notification\_widget.danger.active:focus, .open > .dropdown-toggle.notification\_widget.danger:focus, .notification\_widget.danger:active.focus, .notification\_widget.danger.active.focus, .open > .dropdown-toggle.notification\_widget.danger.focus { color: #fff; background-color: #ac2925; border-color: #761c19; } .notification\_widget.danger:active, .notification\_widget.danger.active, .open > .dropdown-toggle.notification\_widget.danger { background-image: none; } .notification\_widget.danger.disabled:hover, .notification\_widget.danger\[disabled\]:hover, fieldset\[disabled\] .notification\_widget.danger:hover, .notification\_widget.danger.disabled:focus, .notification\_widget.danger\[disabled\]:focus, fieldset\[disabled\] .notification\_widget.danger:focus, .notification\_widget.danger.disabled.focus, .notification\_widget.danger\[disabled\].focus, fieldset\[disabled\] .notification\_widget.danger.focus { background-color: #d9534f; border-color: #d43f3a; } .notification\_widget.danger .badge { color: #d9534f; background-color: #fff; } div#pager { background-color: #fff; font-size: 14px; line-height: 20px; overflow: hidden; display: none; position: fixed; bottom: 0px; width: 100%; max-height: 50%; padding-top: 8px; -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2); box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2); /* Display over codemirror */ z-index: 100; /* Hack which prevents jquery ui resizable from changing top. */ top: auto !important; } div#pager pre { line-height: 1.21429em; color: #000; background-color: #f7f7f7; padding: 0.4em; } div#pager #pager-button-area { position: absolute; top: 8px; right: 20px; } div#pager #pager-contents { position: relative; overflow: auto; width: 100%; height: 100%; } div#pager #pager-contents #pager-container { position: relative; padding: 15px 0px; box-sizing: border-box; -moz-box-sizing: border-box; -webkit-box-sizing: border-box; } div#pager .ui-resizable-handle { top: 0px; height: 8px; background: #f7f7f7; border-top: 1px solid #cfcfcf; border-bottom: 1px solid #cfcfcf; /* This injects handle bars (a short, wide = symbol) for the resize handle. */ } div#pager .ui-resizable-handle::after { content: ''; top: 2px; left: 50%; height: 3px; width: 30px; margin-left: -15px; position: absolute; border-top: 1px solid #cfcfcf; } .quickhelp { /* Old browsers */ display: -webkit-box; -webkit-box-orient: horizontal; -webkit-box-align: stretch; display: -moz-box; -moz-box-orient: horizontal; -moz-box-align: stretch; display: box; box-orient: horizontal; box-align: stretch; /* Modern browsers */ display: flex; flex-direction: row; align-items: stretch; line-height: 1.8em; } .shortcut\_key { display: inline-block; width: 21ex; text-align: right; font-family: monospace; } .shortcut\_descr { display: inline-block; /* Old browsers */ -webkit-box-flex: 1; -moz-box-flex: 1; box-flex: 1; /* Modern browsers */ flex: 1; } span.save\_widget { margin-top: 6px; } span.save\_widget span.filename { height: 1em; line-height: 1em; padding: 3px; margin-left: 16px; border: none; font-size: 146.5%; border-radius: 2px; } span.save\_widget span.filename:hover { background-color: #e6e6e6; } span.checkpoint\_status, span.autosave\_status { font-size: small; } @media (max-width: 767px) { span.save\_widget { font-size: small; } span.checkpoint\_status, span.autosave\_status { display: none; } } @media (min-width: 768px) and (max-width: 991px) { span.checkpoint\_status { display: none; } span.autosave\_status { font-size: x-small; } } .toolbar { padding: 0px; margin-left: -5px; margin-top: 2px; margin-bottom: 5px; box-sizing: border-box; -moz-box-sizing: border-box; -webkit-box-sizing: border-box; } .toolbar select, .toolbar label { width: auto; vertical-align: middle; margin-right: 2px; margin-bottom: 0px; display: inline; font-size: 92%; margin-left: 0.3em; margin-right: 0.3em; padding: 0px; padding-top: 3px; } .toolbar .btn { padding: 2px 8px; } .toolbar .btn-group { margin-top: 0px; margin-left: 5px; } #maintoolbar { margin-bottom: -3px; margin-top: -8px; border: 0px; min-height: 27px; margin-left: 0px; padding-top: 11px; padding-bottom: 3px; } #maintoolbar .navbar-text { float: none; vertical-align: middle; text-align: right; margin-left: 5px; margin-right: 0px; margin-top: 0px; } .select-xs { height: 24px; } .pulse, .dropdown-menu > li > a.pulse, li.pulse > a.dropdown-toggle, li.pulse.open > a.dropdown-toggle { background-color: #F37626; color: white; } /** * Primary styles * * Author: Jupyter Development Team */ /** WARNING IF YOU ARE EDITTING THIS FILE, if this is a .css file, It has a lot * of chance of beeing generated from the ../less/\[samename\].less file, you can * try to get back the less file by reverting somme commit in history **/ /* * We'll try to get something pretty, so we * have some strange css to have the scroll bar on * the left with fix button on the top right of the tooltip */ @-moz-keyframes fadeOut { from { opacity: 1; } to { opacity: 0; } } @-webkit-keyframes fadeOut { from { opacity: 1; } to { opacity: 0; } } @-moz-keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } } @-webkit-keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } } /\*properties of tooltip after "expand"\*/ .bigtooltip { overflow: auto; height: 200px; -webkit-transition-property: height; -webkit-transition-duration: 500ms; -moz-transition-property: height; -moz-transition-duration: 500ms; transition-property: height; transition-duration: 500ms; } /\*properties of tooltip before "expand"\*/ .smalltooltip { -webkit-transition-property: height; -webkit-transition-duration: 500ms; -moz-transition-property: height; -moz-transition-duration: 500ms; transition-property: height; transition-duration: 500ms; text-overflow: ellipsis; overflow: hidden; height: 80px; } .tooltipbuttons { position: absolute; padding-right: 15px; top: 0px; right: 0px; } .tooltiptext { /\*avoid the button to overlap on some docstring\*/ padding-right: 30px; } .ipython\_tooltip { max-width: 700px; /\*fade-in animation when inserted\*/ -webkit-animation: fadeOut 400ms; -moz-animation: fadeOut 400ms; animation: fadeOut 400ms; -webkit-animation: fadeIn 400ms; -moz-animation: fadeIn 400ms; animation: fadeIn 400ms; vertical-align: middle; background-color: #f7f7f7; overflow: visible; border: #ababab 1px solid; outline: none; padding: 3px; margin: 0px; padding-left: 7px; font-family: monospace; min-height: 50px; -moz-box-shadow: 0px 6px 10px -1px #adadad; -webkit-box-shadow: 0px 6px 10px -1px #adadad; box-shadow: 0px 6px 10px -1px #adadad; border-radius: 2px; position: absolute; z-index: 1000; } .ipython\_tooltip a { float: right; } .ipython_tooltip .tooltiptext pre { border: 0; border-radius: 0; font-size: 100%; background-color: #f7f7f7; } .pretooltiparrow { left: 0px; margin: 0px; top: -16px; width: 40px; height: 16px; overflow: hidden; position: absolute; } .pretooltiparrow:before { background-color: #f7f7f7; border: 1px #ababab solid; z-index: 11; content: ""; position: absolute; left: 15px; top: 10px; width: 25px; height: 25px; -webkit-transform: rotate(45deg); -moz-transform: rotate(45deg); -ms-transform: rotate(45deg); -o-transform: rotate(45deg); } ul.typeahead-list i { margin-left: -10px; width: 18px; } ul.typeahead-list { max-height: 80vh; overflow: auto; } ul.typeahead-list > li > a { /** Firefox bug **/ /* see https://github.com/jupyter/notebook/issues/559 */ white-space: normal; } .cmd-palette .modal-body { padding: 7px; } .cmd-palette form { background: white; } .cmd-palette input { outline: none; } .no-shortcut { display: none; } .command-shortcut:before { content: "(command)"; padding-right: 3px; color: #777777; } .edit-shortcut:before { content: "(edit)"; padding-right: 3px; color: #777777; } #find-and-replace #replace-preview .match, #find-and-replace #replace-preview .insert { background-color: #BBDEFB; border-color: #90CAF9; border-style: solid; border-width: 1px; border-radius: 0px; } #find-and-replace #replace-preview .replace .match { background-color: #FFCDD2; border-color: #EF9A9A; border-radius: 0px; } #find-and-replace #replace-preview .replace .insert { background-color: #C8E6C9; border-color: #A5D6A7; border-radius: 0px; } #find-and-replace #replace-preview { max-height: 60vh; overflow: auto; } #find-and-replace #replace-preview pre { padding: 5px 10px; } .terminal-app { background: #EEE; } .terminal-app #header { background: #fff; -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2); box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2); } .terminal-app .terminal { width: 100%; float: left; font-family: monospace; color: white; background: black; padding: 0.4em; border-radius: 2px; -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4); box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4); } .terminal-app .terminal, .terminal-app .terminal dummy-screen { line-height: 1em; font-size: 14px; } .terminal-app .terminal .xterm-rows { padding: 10px; } .terminal-app .terminal-cursor { color: black; background: white; } .terminal-app #terminado-container { margin-top: 20px; } /*# sourceMappingURL=style.min.css.map */   .highlight .hll { background-color: #ffffcc } .highlight { background: #f8f8f8; } .highlight .c { color: #408080; font-style: italic } /* Comment */ .highlight .err { border: 1px solid #FF0000 } /* Error */ .highlight .k { color: #008000; font-weight: bold } /* Keyword */ .highlight .o { color: #666666 } /* Operator */ .highlight .ch { color: #408080; font-style: italic } /* Comment.Hashbang */ .highlight .cm { color: #408080; font-style: italic } /* Comment.Multiline */ .highlight .cp { color: #BC7A00 } /* Comment.Preproc */ .highlight .cpf { color: #408080; font-style: italic } /* Comment.PreprocFile */ .highlight .c1 { color: #408080; font-style: italic } /* Comment.Single */ .highlight .cs { color: #408080; font-style: italic } /* Comment.Special */ .highlight .gd { color: #A00000 } /* Generic.Deleted */ .highlight .ge { font-style: italic } /* Generic.Emph */ .highlight .gr { color: #FF0000 } /* Generic.Error */ .highlight .gh { color: #000080; font-weight: bold } /* Generic.Heading */ .highlight .gi { color: #00A000 } /* Generic.Inserted */ .highlight .go { color: #888888 } /* Generic.Output */ .highlight .gp { color: #000080; font-weight: bold } /* Generic.Prompt */ .highlight .gs { font-weight: bold } /* Generic.Strong */ .highlight .gu { color: #800080; font-weight: bold } /* Generic.Subheading */ .highlight .gt { color: #0044DD } /* Generic.Traceback */ .highlight .kc { color: #008000; font-weight: bold } /* Keyword.Constant */ .highlight .kd { color: #008000; font-weight: bold } /* Keyword.Declaration */ .highlight .kn { color: #008000; font-weight: bold } /* Keyword.Namespace */ .highlight .kp { color: #008000 } /* Keyword.Pseudo */ .highlight .kr { color: #008000; font-weight: bold } /* Keyword.Reserved */ .highlight .kt { color: #B00040 } /* Keyword.Type */ .highlight .m { color: #666666 } /* Literal.Number */ .highlight .s { color: #BA2121 } /* Literal.String */ .highlight .na { color: #7D9029 } /* Name.Attribute */ .highlight .nb { color: #008000 } /* Name.Builtin */ .highlight .nc { color: #0000FF; font-weight: bold } /* Name.Class */ .highlight .no { color: #880000 } /* Name.Constant */ .highlight .nd { color: #AA22FF } /* Name.Decorator */ .highlight .ni { color: #999999; font-weight: bold } /* Name.Entity */ .highlight .ne { color: #D2413A; font-weight: bold } /* Name.Exception */ .highlight .nf { color: #0000FF } /* Name.Function */ .highlight .nl { color: #A0A000 } /* Name.Label */ .highlight .nn { color: #0000FF; font-weight: bold } /* Name.Namespace */ .highlight .nt { color: #008000; font-weight: bold } /* Name.Tag */ .highlight .nv { color: #19177C } /* Name.Variable */ .highlight .ow { color: #AA22FF; font-weight: bold } /* Operator.Word */ .highlight .w { color: #bbbbbb } /* Text.Whitespace */ .highlight .mb { color: #666666 } /* Literal.Number.Bin */ .highlight .mf { color: #666666 } /* Literal.Number.Float */ .highlight .mh { color: #666666 } /* Literal.Number.Hex */ .highlight .mi { color: #666666 } /* Literal.Number.Integer */ .highlight .mo { color: #666666 } /* Literal.Number.Oct */ .highlight .sa { color: #BA2121 } /* Literal.String.Affix */ .highlight .sb { color: #BA2121 } /* Literal.String.Backtick */ .highlight .sc { color: #BA2121 } /* Literal.String.Char */ .highlight .dl { color: #BA2121 } /* Literal.String.Delimiter */ .highlight .sd { color: #BA2121; font-style: italic } /* Literal.String.Doc */ .highlight .s2 { color: #BA2121 } /* Literal.String.Double */ .highlight .se { color: #BB6622; font-weight: bold } /* Literal.String.Escape */ .highlight .sh { color: #BA2121 } /* Literal.String.Heredoc */ .highlight .si { color: #BB6688; font-weight: bold } /* Literal.String.Interpol */ .highlight .sx { color: #008000 } /* Literal.String.Other */ .highlight .sr { color: #BB6688 } /* Literal.String.Regex */ .highlight .s1 { color: #BA2121 } /* Literal.String.Single */ .highlight .ss { color: #19177C } /* Literal.String.Symbol */ .highlight .bp { color: #008000 } /* Name.Builtin.Pseudo */ .highlight .fm { color: #0000FF } /* Name.Function.Magic */ .highlight .vc { color: #19177C } /* Name.Variable.Class */ .highlight .vg { color: #19177C } /* Name.Variable.Global */ .highlight .vi { color: #19177C } /* Name.Variable.Instance */ .highlight .vm { color: #19177C } /* Name.Variable.Magic */ .highlight .il { color: #666666 } /* Literal.Number.Integer.Long */   /\* Temporary definitions which will become obsolete with Notebook release 5.0 */ .ansi-black-fg { color: #3E424D; } .ansi-black-bg { background-color: #3E424D; } .ansi-black-intense-fg { color: #282C36; } .ansi-black-intense-bg { background-color: #282C36; } .ansi-red-fg { color: #E75C58; } .ansi-red-bg { background-color: #E75C58; } .ansi-red-intense-fg { color: #B22B31; } .ansi-red-intense-bg { background-color: #B22B31; } .ansi-green-fg { color: #00A250; } .ansi-green-bg { background-color: #00A250; } .ansi-green-intense-fg { color: #007427; } .ansi-green-intense-bg { background-color: #007427; } .ansi-yellow-fg { color: #DDB62B; } .ansi-yellow-bg { background-color: #DDB62B; } .ansi-yellow-intense-fg { color: #B27D12; } .ansi-yellow-intense-bg { background-color: #B27D12; } .ansi-blue-fg { color: #208FFB; } .ansi-blue-bg { background-color: #208FFB; } .ansi-blue-intense-fg { color: #0065CA; } .ansi-blue-intense-bg { background-color: #0065CA; } .ansi-magenta-fg { color: #D160C4; } .ansi-magenta-bg { background-color: #D160C4; } .ansi-magenta-intense-fg { color: #A03196; } .ansi-magenta-intense-bg { background-color: #A03196; } .ansi-cyan-fg { color: #60C6C8; } .ansi-cyan-bg { background-color: #60C6C8; } .ansi-cyan-intense-fg { color: #258F8F; } .ansi-cyan-intense-bg { background-color: #258F8F; } .ansi-white-fg { color: #C5C1B4; } .ansi-white-bg { background-color: #C5C1B4; } .ansi-white-intense-fg { color: #A1A6B2; } .ansi-white-intense-bg { background-color: #A1A6B2; } .ansi-bold { font-weight: bold; }   /\* Overrides of notebook CSS for static HTML export */ body { overflow: visible; padding: 8px; } div#notebook { overflow: visible; border-top: none; }@media print { div.cell { display: block; page-break-inside: avoid; } div.output_wrapper { display: block; page-break-inside: avoid; } div.output { display: block; page-break-inside: avoid; } }         MathJax.Hub.Config({ tex2jax: { inlineMath: \[ \['$','$'\], \["\\\(","\\\)"\] \], displayMath: \[ \['$$','$$'\], \["\\\\[","\\\\]"\] \], processEscapes: true, processEnvironments: true }, // Center justify equations in code and markdown cells. Elsewhere // we use CSS to left justify single line equations in code cells. displayAlign: 'center', "HTML-CSS": { styles: {'.MathJax_Display': {"margin": 0}}, linebreaks: { automatic: true } } });  

Self-Driving Car Engineer Nanodegree[¶](#Self-Driving-Car-Engineer-Nanodegree)
==============================================================================

Deep Learning[¶](#Deep-Learning)
--------------------------------

Project: Build a Traffic Sign Recognition Classifier[¶](#Project:-Build-a-Traffic-Sign-Recognition-Classifier)
--------------------------------------------------------------------------------------------------------------

In this notebook, a template is provided for you to implement your functionality in stages, which is required to successfully complete this project. If additional code is required that cannot be included in the notebook, be sure that the Python code is successfully imported and included in your submission if necessary.

> **Note**: Once you have completed all of the code implementations, you need to finalize your work by exporting the iPython Notebook as an HTML document. Before exporting the notebook to html, all of the code cells need to have been run so that reviewers can see the final implementation and output. You can then export the notebook by using the menu above and navigating to \\n", "**File -> Download as -> HTML (.html)**. Include the finished document along with this notebook as your submission.

In addition to implementing code, there is a writeup to complete. The writeup should be completed in a separate file, which can be either a markdown file or a pdf document. There is a [write up template](https://github.com/udacity/CarND-Traffic-Sign-Classifier-Project/blob/master/writeup_template.md) that can be used to guide the writing process. Completing the code template and writeup template will cover all of the [rubric points](https://review.udacity.com/#!/rubrics/481/view) for this project.

The [rubric](https://review.udacity.com/#!/rubrics/481/view) contains "Stand Out Suggestions" for enhancing the project beyond the minimum requirements. The stand out suggestions are optional. If you decide to pursue the "stand out suggestions", you can include the code in this Ipython notebook and also discuss the results in the writeup file.

> **Note:** Code and Markdown cells can be executed using the **Shift + Enter** keyboard shortcut. In addition, Markdown cells can be edited by typically double-clicking the cell to enter edit mode.

* * *

Step 0: Load The Data[¶](#Step-0:-Load-The-Data)
------------------------------------------------

In \[1\]:

import pickle

\# Files for downloading, https://d17h27t6h515a5.cloudfront.net/topher/2017/February/5898cd6f_traffic-signs-data/traffic-signs-data.zip

\# Loading data with pickle library

training_file = 'traffic-signs-data/train.p'
validation_file = 'traffic-signs-data/valid.p'
testing_file = 'traffic-signs-data/test.p'

with open(training_file, mode='rb') as f:
    train = pickle.load(f)
with open(validation_file, mode='rb') as f:
    valid = pickle.load(f)
with open(testing_file, mode='rb') as f:
    test = pickle.load(f)
    
X_train, y_train = train\['features'\], train\['labels'\]
X_valid, y_valid = valid\['features'\], valid\['labels'\]
X_test, y_test = test\['features'\], test\['labels'\]

print("Done")

Done

* * *

Step 1: Dataset Summary & Exploration[¶](#Step-1:-Dataset-Summary-&-Exploration)
--------------------------------------------------------------------------------

The pickled data is a dictionary with 4 key/value pairs:

*   `'features'` is a 4D array containing raw pixel data of the traffic sign images, (num examples, width, height, channels).
*   `'labels'` is a 1D array containing the label/class id of the traffic sign. The file `signnames.csv` contains id -> name mappings for each id.
*   `'sizes'` is a list containing tuples, (width, height) representing the original width and height the image.
*   `'coords'` is a list containing tuples, (x1, y1, x2, y2) representing coordinates of a bounding box around the sign in the image. **THESE COORDINATES ASSUME THE ORIGINAL IMAGE. THE PICKLED DATA CONTAINS RESIZED VERSIONS (32 by 32) OF THESE IMAGES**

Complete the basic data summary below. Use python, numpy and/or pandas methods to calculate the data summary rather than hard coding the results. For example, the [pandas shape method](http://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.shape.html) might be useful for calculating some of the summary results.

### Provide a Basic Summary of the Data Set Using Python, Numpy and/or Pandas[¶](#Provide-a-Basic-Summary-of-the-Data-Set-Using-Python,-Numpy-and/or-Pandas)

In \[2\]:

\# Dimensions of data

n_train = X_train.shape\[0\]
n_validation = X_valid.shape\[0\]
n_test = X_test.shape\[0\]
image_shape = X_train\[0\].shape
n_classes = len(set(y_train))

print("Size of training set =", n_train)
print("Size of validation set =", n_validation)
print("Size of test set =", n_test)
print("Shape of a traffic sign image =", image_shape)
print("Number of classes =", n_classes)

Size of training set = 34799
Size of validation set = 4410
Size of test set = 12630
Shape of a traffic sign image = (32, 32, 3)
Number of classes = 43

### Include an exploratory visualization of the dataset[¶](#Include-an-exploratory-visualization-of-the-dataset)

Visualize the German Traffic Signs Dataset using the pickled file(s). This is open ended, suggestions include: plotting traffic sign images, plotting the count of each sign, etc.

The [Matplotlib](http://matplotlib.org/) [examples](http://matplotlib.org/examples/index.html) and [gallery](http://matplotlib.org/gallery.html) pages are a great resource for doing visualizations in Python.

**NOTE:** It's recommended you start with something simple first. If you wish to do more, come back to it after you've completed the rest of the sections. It can be interesting to look at the distribution of classes in the training, validation and test set. Is the distribution the same? Are there more examples of some classes than others?

In \[3\]:

import numpy as np
import matplotlib.pyplot as plt
import random
%matplotlib inline

\# Visualizing training set

fig, axs = plt.subplots(3,3, figsize=(10, 10))
axs = axs.ravel()
for i in range(9):
    index = np.random.randint(len(X_train))
    image = X_train\[index\]
    axs\[i\].axis('off')
    axs\[i\].imshow(image)
    axs\[i\].set_title(y_train\[index\])

![](data:image/png;base64,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
9yTb/gOtWP7QL35Osgdu/rJkX3r2jGTjXJ8VtWCqUTd1rC8d0wUB3eNHJJut6cKUyDzfVgeaff+s
VmPfdb++cACxVbhLf9hFtvS1RHWz8CQywn/mpGrz3HTVsK0IXtNxYzPTZld5vfx3IvrZvNDjBvO+
y1z19Ex/iaIwz2v3jnEV393iINenbrzYkW4OciV3BN88AQAAAFSAyRMAAABABZg8AQAAAFSAyRMA
AABABfZZGFc9y1UE395V0frC8uuSjUyl79jIY5NMBbXMZblWbHbVVetGGEwmKsulI91fvXtIsunr
TknWnXbCoB7j8plzko23Vd6td7Uq9FTLVP9uGeHeSI6Npsr6XVOxvN1y1b/1PEZGIo9q2r7EjCFX
Ydy4hgeSVqLjdauvkv3RpXnJJn09yZcu6KKCyPTZoQXts8GuXvuzu1rBvjWjonp/Xcf6HTddL9nn
Th+TbO9//y3Jwqye7/FPq+DdvUkXWyw89aRklx5TKX1y5kHJ/syf/BOSPfXq35Jsc6TPgP6eWcxg
JPJhpuN6Y1l/aaF9Svtg7YLe2y+8pNdoZVWfjXl6bVTddwp0ebHX/vSBRElsXn1ODjeLarzQbmRk
I33XzCKn2C2gcZXDTXVtr9a7PjCRE62dlO4qgpv+y1M9SJbqcyE3C3xsn5o2J+ZdlBp5vdyypxCu
ZGXRNfKKAQAAADgYMHkCAAAAqACTJwAAAIAKMHkCAAAAqMBVrzBepCpstadUbp6e1urHaari8SRV
VSzPjChpBDWrAZpKwg0nm++p5B4K7d7OwpJkU4uLkrW7+tl0qNXE+xtaibl/eU+y+tSUZIcXtKpx
o6eS6p6RY5NExcd6U0XYwlR1TU2fJoXp59zN7bXv2039bCfRsXEQeeLps5J151S8P9HU83ltSxcL
tBvaP7sDzWYSrXQ/MNdgZOT14Vhl5LG5jz/y2U9LVnv+WT3GplY7733m35Js6rZbJYsaep8c+vTP
SLbzvRck2/zqlyS76y/8gmQP3f37kv3OEy9LFnK9T7p1vW7jLRXzO229Rt999rxkh8wvHkz65Rar
BCPbHkTcLz04ubms6hsZ+dpV6y4y7TMvMpv2JUYOr+s9Ficlv68oWzXbmuB2h5qU3s4I44np00jf
CXZ/hXk2u1+YsL924eR/zTJb8d3x7muM880TAAAAQAWYPAEAAABUgMkTAAAAQAWYPAEAAABUYF+F
8c11rYSbr69LNt5UCfrZNZWlN0YqgmfGgiuCipKuaqqT9MJYxbN0T4XsYqASbWtqRrLukgrj9Z4K
8nFL29w5dFiymcNr2r4drcY+MW2udXqSNZralo2ByvC7A1NNeUevR2qqyWYuK4zA6YxGE3W6+tlD
HZV3DyLb6WXJXj5zSTInaR85rIsADiV6Tc+vqZB9dlOlzb1Mx9xwrNc+yrS/T998l2QPTs9K1v/9
/1Oy+oIR5D/7Kcnihkq5jsYt90g296F7JVv5wtOS5c+dkezP/fyfleyV1f9Jst6s3u8L07qIIqtp
P+9saOXwvbEKzO2e7u+GG/WaT0xl7F5Pr8eBxFbwNhhx2xEb4TkyC09yIy07eT1Eev1iI4w7Ub0w
2rI9CydLu6Lj9tNGaHenYfuvZGY3M/3sKqqbfs5yI5Gbiuq2eLoT+COzoTfk3zV88wQAAABQASZP
AAAAABVg8gQAAABQASZPAAAAABXYV2H8v/zv/o5kGy9+T7LLG1qBd9f4v2mmYW6yiSkw7iqQ1kzV
1NlYpc3u3q5kiama3ZzVat3dhQXJGg0nr2v74pYKwu3Fo5oZMX+0olm0oxJ5s6tVcRuJSqqTiQp+
I9MHzv100qRVREs6f5kRmCemLQeRZ155SbJVUyG+lqikOj2lCwgah+ckW5rVe+LFN1VK3xvpNY3M
OEzqXck+/cnPSNZ89buSDXf13u59UiuCd264UbLStLR9c5/8Wcn2ntZnz+7XvyDZLf/hvyfZ5x++
U7IvvqQVwfdM/22s6+KXhUMqHJ9MNYtj/aWFhTm95qOBjpe5Ge2XawX76w92OyMtG5E5FPpSsNs5
VzrW65KYd0c20bGem/eOc5tLYxY+JaayeWKeH0609gJ6SZwwbk4uNm1x72170V1WcvFXYe5FL82X
g2+eAAAAACrA5AkAAACgAkyeAAAAACrA5AkAAACgAvsqjH/t9/9IssHQbGjErtyZwrYSrRPFzGax
SmvdhpMItbJzYao9x0ZSbS+p0NvsagXvzFQSXlldlmxzR6s9t2p6CTuLetzBllYwHve18nR7SqsV
L0xpm3eHeo0mfZX+MlsW11XZNfJiSZnPVu01UuJBpGtk92ZPhc9OU6X9pjnv715elezoQBc4DIZm
DJt7LDUy5k333izZw7eotLz7m89KFpkq+UuPflqyUNdxbStAmyrObizVb7pDsulHPiLZxX/+Jcm2
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
)

In \[4\]:

\# Plotting the count of each sign
\# Showing the distribution of classes in the training, validation and test set

import matplotlib.pyplot as plt
import random
%matplotlib inline

fig, axs = plt.subplots(1,3, figsize=(20, 5))
axs = axs.ravel()

Data = \[np.histogram(y_train, bins=n_classes), np.histogram(y_valid, bins=n_classes), np.histogram(y_test, bins=n_classes)\]
labels = \['Train data', 'Validate data', 'Test data'\]

hist = \[Data\[0\]\[0\], Data\[1\]\[0\], Data\[2\]\[0\]\]
bins = \[Data\[0\]\[1\], Data\[1\]\[1\], Data\[2\]\[1\]\]

for i in range(3):
    width = 0.7 * (bins\[i\]\[1\] - bins\[i\]\[0\])
    center = (bins\[i\]\[:-1\] + bins\[i\]\[1:\]) / 2
    axs\[i\].bar(center, hist\[i\], width=width)
    axs\[i\].set_title(labels\[i\])

![](data:image/png;base64,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
AAAASUVORK5CYII=
)

* * *

Step 2: Design and Test a Model Architecture[¶](#Step-2:-Design-and-Test-a-Model-Architecture)
----------------------------------------------------------------------------------------------

Design and implement a deep learning model that learns to recognize traffic signs. Train and test your model on the [German Traffic Sign Dataset](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset).

The LeNet-5 implementation shown in the [classroom](https://classroom.udacity.com/nanodegrees/nd013/parts/fbf77062-5703-404e-b60c-95b78b2f3f9e/modules/6df7ae49-c61c-4bb2-a23e-6527e69209ec/lessons/601ae704-1035-4287-8b11-e2c2716217ad/concepts/d4aca031-508f-4e0b-b493-e7b706120f81) at the end of the CNN lesson is a solid starting point. You'll have to change the number of classes and possibly the preprocessing, but aside from that it's plug and play!

With the LeNet-5 solution from the lecture, you should expect a validation set accuracy of about 0.89. To meet specifications, the validation set accuracy will need to be at least 0.93. It is possible to get an even higher accuracy, but 0.93 is the minimum for a successful project submission.

There are various aspects to consider when thinking about this problem:

*   Neural network architecture (is the network over or underfitting?)
*   Play around preprocessing techniques (normalization, rgb to grayscale, etc)
*   Number of examples per label (some have more than others).
*   Generate fake data.

Here is an example of a [published baseline model on this problem](http://yann.lecun.com/exdb/publis/pdf/sermanet-ijcnn-11.pdf). It's not required to be familiar with the approach used in the paper but, it's good practice to try to read papers like these.

### Pre-process the Data Set (normalization, grayscale, etc.)[¶](#Pre-process-the-Data-Set-(normalization,-grayscale,-etc.))

Minimally, the image data should be normalized so that the data has mean zero and equal variance. For image data, `(pixel - 128)/ 128` is a quick way to approximately normalize the data and can be used in this project.

Other pre-processing steps are optional. You can try different techniques to see if it improves performance.

Use the code cell (or multiple code cells, if necessary) to implement the first step of your project.

In \[5\]:

import numpy as np

\# Train Data
\# Formula to convert rgb to gray
\# Y = 0.299 x R + 0.587 x G + 0.114 x B
\# but the mean works well.

X\_train\_rgb = X_train
X\_train\_gray = np.sum(X_train/3, axis=3, keepdims=True)

X\_valid\_rgb = X_valid
X\_valid\_gray = np.sum(X_valid/3, axis=3, keepdims=True)

X\_test\_rgb = X_test
X\_test\_gray = np.sum(X_test/3, axis=3, keepdims=True)

In \[6\]:

\# Images RGB and Gray

import numpy as np
import matplotlib.pyplot as plt

n_rows, n_cols = 4, 2

fig, axs = plt.subplots(n_rows,n_cols, figsize=(18, 14))
axs = axs.ravel()

for i in range(4):
    numb = np.random.randint(len(X_train))
    axs\[i*2\].imshow(X\_train\_rgb\[numb\])
    axs\[i*2+1\].imshow(X\_train\_gray\[numb\].squeeze(), cmap='gray')

axs\[0\].set_title('Image RGB')
axs\[1\].set_title('Image Gray')

plt.show()

![](data:image/png;base64,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
)

In \[7\]:

\# Normalize data
X\_train\_gray_norm = (X\_train\_gray - 128) / 128.0
X\_valid\_gray_norm = (X\_valid\_gray - 128) / 128.0
X\_test\_gray_norm = (X\_test\_gray - 128) / 128.0

print(np.mean(X\_train\_gray_norm))
print(np.mean(X\_valid\_gray_norm))
print(np.mean(X\_test\_gray_norm))

-0.354081335648
-0.347215411128
-0.358215153428

In \[8\]:

\### Shuffle training dataset

from sklearn.utils import shuffle

X\_train\_gray_norm, y\_train\_gray = shuffle(X\_train\_gray_norm, y_train)

### Model Architecture[¶](#Model-Architecture)

In \[9\]:

\### Define your architecture here.
\### Feel free to use as many code cells as needed.

import tensorflow as tf
from tensorflow.contrib.layers import flatten

def LeNet(x):
    \# Hyperparameteres
    mu = 0
    sigma = 0.1
    
    
    \# Layer 1: Convolutional. Input 32 x 32 x 1. Output 28 x 28 x 6
    conv1_W = tf.Variable(tf.truncated_normal(shape=(5, 5, 1, 6), mean = mu, stddev = sigma))
    conv1_b = tf.Variable(tf.zeros(6))
    conv1 = tf.nn.conv2d(x, conv1_W, strides=\[1, 1, 1, 1\], padding = 'VALID') + conv1_b
    conv1 = tf.nn.relu(conv1)
    
    \# Layer 2: Pooling. Input 28 x 28 x 6. Output 14 x 14 x 6
    pool1 = tf.nn.max_pool(conv1, ksize=\[1, 2, 2, 1\], strides=\[1, 2, 2, 1\], padding='VALID')
    
    
    \# Layer 3: Convolutional. Input 14 x 14 x 6. Output 10 x 10 x 16
    conv2_W = tf.Variable(tf.truncated_normal(shape=(5, 5, 6, 16), mean = mu, stddev=sigma))
    conv2_b = tf.Variable(tf.zeros(16))
    conv2 = tf.nn.conv2d(pool1, conv2_W, strides=\[1, 1, 1, 1\], padding='VALID') + conv2_b
    conv2 = tf.nn.relu(conv2)
    
    \# Layer 4: Pooling. Input 10 x 10 x 16. Output 5 x 5 x 16
    pool2 = tf.nn.max_pool(conv2, ksize=\[1, 2, 2, 1\], strides=\[1, 2, 2, 1\], padding='VALID')
    
    \# Layer 5: Flatten. Input 5 x 5 x 16. Output 400
    fc0 = flatten(pool2)
    
    \# Layer 6: Fully Connected. Input 400. Output 120.
    fc1_W = tf.Variable(tf.truncated_normal(shape=(400, 120), mean=mu, stddev=sigma))
    fc1_b = tf.Variable(tf.zeros(120))
    fc1 = tf.matmul(fc0, fc1_W) + fc1_b
    fc1 = tf.nn.relu(fc1)
    
    \# Layer 7: Fully Connected. Input 120. Output 84.
    fc2_W = tf.Variable(tf.truncated_normal(shape=(120, 84), mean=mu, stddev=sigma))
    fc2_b = tf.Variable(tf.zeros(84))
    fc2 = tf.matmul(fc1, fc2_W) + fc2_b
    fc2 = tf.nn.relu(fc2)
    
    \# Layer 8: Fully Connected. Input 84. Output 43.
    fc3_W = tf.Variable(tf.truncated_normal(shape=(84, 43), mean=mu, stddev=sigma))
    fc3_b = tf.Variable(tf.zeros(43))
    logits = tf.matmul(fc2, fc3_W) + fc3_b

    return logits

In \[10\]:

\### Define your architecture here.
\### Feel free to use as many code cells as needed.

import tensorflow as tf
from tensorflow.contrib.layers import flatten

def LeNet_2(x):
    \# Hyperparameteres
    mu = 0
    sigma = 0.1
    
    
    \# Layer 1: Convolutional. Input 32 x 32 x 1. Output 28 x 28 x 6
    conv1_W = tf.Variable(tf.truncated_normal(shape=(5, 5, 1, 6), mean = mu, stddev = sigma))
    conv1_b = tf.Variable(tf.zeros(6))
    conv1 = tf.nn.conv2d(x, conv1_W, strides=\[1, 1, 1, 1\], padding = 'VALID') + conv1_b
    conv1 = tf.nn.relu(conv1)
    
    \# Layer 2: Pooling. Input 28 x 28 x 6. Output 14 x 14 x 6
    pool1 = tf.nn.max_pool(conv1, ksize=\[1, 2, 2, 1\], strides=\[1, 2, 2, 1\], padding='VALID')
    
    
    \# Layer 3: Convolutional. Input 14 x 14 x 6. Output 10 x 10 x 16
    conv2_W = tf.Variable(tf.truncated_normal(shape=(5, 5, 6, 16), mean = mu, stddev=sigma))
    conv2_b = tf.Variable(tf.zeros(16))
    conv2 = tf.nn.conv2d(pool1, conv2_W, strides=\[1, 1, 1, 1\], padding='VALID') + conv2_b
    conv2 = tf.nn.relu(conv2)
    
    \# Layer 4: Pooling. Input 10 x 10 x 16. Output 5 x 5 x 16
    pool2 = tf.nn.max_pool(conv2, ksize=\[1, 2, 2, 1\], strides=\[1, 2, 2, 1\], padding='VALID')
    
    \# Layer 5: Convolutional. Input 5 x 5 x 16. Output 1 x 1 x 120 
    conv3_W = tf.Variable(tf.truncated_normal(shape=(5, 5, 16, 120)))
    conv3_b = tf.Variable(tf.zeros(120))
    conv3 = tf.nn.conv2d(pool2, conv3_W, strides=\[1, 1, 1, 1\], padding='VALID')
    conv3 = tf.nn.relu(conv3)
    
    \# Layer 6: Flatten. Input 1 x 1 x 120. Output 120
    fc0 = flatten(conv3)
    
    \# Layer 7: Fully Connected. Input 120. Output 64.
    fc1_W = tf.Variable(tf.truncated_normal(shape=(120, 64), mean=mu, stddev=sigma))
    fc1_b = tf.Variable(tf.zeros(64))
    fc1 = tf.add(tf.matmul(fc0, fc1_W), fc1_b)
    fc1 = tf.nn.relu(fc1)
    
    \# Layer 8: Fully Connected. Input 64. Output 43.
    fc2_W = tf.Variable(tf.truncated_normal(shape=(64, 43), mean=mu, stddev=sigma))
    fc2_b = tf.Variable(tf.zeros(43))
    logits = tf.add(tf.matmul(fc1, fc2_W), fc2_b)

    return logits

In \[11\]:

import tensorflow as tf
from tensorflow.contrib.layers import flatten

def LeNet_3(x):    
    \# Hyperparameters
    mu = 0
    sigma = 0.1
    
    \# TODO: Layer 1: Convolutional. Input = 32x32x1. Output = 28x28x6.
    conv1_W = tf.Variable(tf.truncated_normal(shape=(5, 5, 1, 6), mean = mu, stddev = sigma), name="conv1_W")
    conv1_b = tf.Variable(tf.zeros(6), name="conv1_b")
    conv1 = tf.nn.conv2d(x, conv1_W, strides=\[1, 1, 1, 1\], padding='VALID')
    conv1 = tf.nn.bias_add(conv1, conv1_b)
    print("conv1 shape:",conv1.get_shape())

    \# TODO: Activation.
    conv1 = tf.nn.relu(conv1)
    
    \# TODO: Pooling. Input = 28x28x6. Output = 14x14x6.
    pool1 = tf.nn.max_pool(conv1, ksize=\[1, 2, 2, 1\], strides=\[1, 2, 2, 1\], padding='VALID')
    
    \# TODO: Layer 2: Convolutional. Output = 10x10x16.
    conv2_W = tf.Variable(tf.truncated_normal(shape=(5, 5, 6, 16), mean = mu, stddev = sigma), name="conv2_W")
    conv2_b = tf.Variable(tf.zeros(16), name="conv2_b")
    conv2 = tf.nn.conv2d(pool1, conv2_W, strides=\[1, 1, 1, 1\], padding='VALID')
    conv2 = tf.nn.bias_add(conv2, conv2_b)
                     
    \# TODO: Activation.
    conv2 = tf.nn.relu(conv2)

    \# TODO: Pooling. Input = 10x10x16. Output = 5x5x16.
    pool2 = tf.nn.max_pool(conv2, ksize=\[1, 2, 2, 1\], strides=\[1, 2, 2, 1\], padding='VALID')
    
    \# TODO: Layer 3: Convolutional. Output = 1x1x400.
    conv3_W = tf.Variable(tf.truncated_normal(shape=(5, 5, 16, 400), mean = mu, stddev = sigma), name="conv3_W")
    conv3_b = tf.Variable(tf.zeros(400), name="conv3_b")
    conv3 = tf.nn.conv2d(pool2, conv3_W, strides=\[1, 1, 1, 1\], padding='VALID')
    conv3 = tf.nn.bias_add(conv3, conv3_b)
                     
    \# TODO: Activation.
    conv3 = tf.nn.relu(conv3)
    
    \# TODO: Flatten. Input = 5x5x16. Output = 400.
    extra_flatten = flatten(pool2)
    
    \# Flatten x. Input = 1x1x400. Output = 400.
    fc0 = flatten(conv3)

    \# Concat extra_flatten and fc0. Input = 400 + 400. Output = 800
    fc1 = tf.concat_v2(\[fc0, extra_flatten\], 1)
    
    \# Dropout
    fc1 = tf.nn.dropout(fc1, keep_prob)
    
    \# TODO: Layer 4: Fully Connected. Input = 800. Output = 43.
    fc2_W = tf.Variable(tf.truncated_normal(shape=(800, 43), mean = mu, stddev = sigma), name="fc2_W")
    fc2_b = tf.Variable(tf.zeros(43), name="fc2_b")    
    logits = tf.add(tf.matmul(fc1, fc2_W), fc2_b)
    
    return logits

print('done')

done

In \[12\]:

import tensorflow as tf
tf.\_\_version\_\_

Out\[12\]:

'0.12.0'

In \[13\]:

X = tf.placeholder(tf.float32, (None, 32, 32, 1))
y = tf.placeholder(tf.int32, (None))
one\_hot\_y = tf.one_hot(y, 43)
keep_prob = tf.placeholder(tf.float32)

### Train, Validate and Test the Model[¶](#Train,-Validate-and-Test-the-Model)

A validation set can be used to assess how well the model is performing. A low accuracy on the training and validation sets imply underfitting. A high accuracy on the training set but low accuracy on the validation set implies overfitting.

In \[14\]:

\### Train your model here.
\### Calculate and report the accuracy on the training and validation set.
\### Once a final model architecture is selected, 
\### the accuracy on the test set should be calculated and reported as well.
\### Feel free to use as many code cells as needed.

\# Train
rate = 9 * 1e-4

logits = LeNet_3(X)
cross_entropy = tf.nn.softmax\_cross\_entropy\_with\_logits(logits=logits, labels=one\_hot\_y)
#logits_softmax = tf.nn.softmax(logits)
#cross\_entropy = -tf.reduce\_sum(one\_hot\_y * tf.log(logits_softmax),\[1\])
loss_operation = tf.reduce_mean(cross_entropy)
optimizer = tf.train.AdamOptimizer(learning_rate=rate)
training_operation = optimizer.minimize(loss_operation)

conv1 shape: (?, 28, 28, 6)

In \[15\]:

\# Evaluation
correct_prediction = tf.equal(tf.argmax(logits, 1), tf.argmax(one\_hot\_y, 1))
accuracy_operation = tf.reduce_mean(tf.cast(correct_prediction, tf.float32))

def evaluate(X_data, y_data):
    steps\_per\_epoch = len(X_data) // BATCH_SIZE
    num_examples = steps\_per\_epoch * BATCH_SIZE
    if num_examples == 0:
        num_examples = len(X_data)
    total_accuracy, total_loss = 0, 0
    sess = tf.get\_default\_session()
    for offnet in range(0, num_examples, BATCH_SIZE):
        end = offnet + BATCH_SIZE
        batch_x, batch_y = X_data\[offnet:end\], y_data\[offnet:end\]
        loss, accuracy = sess.run(\[loss_operation, accuracy_operation\], feed_dict={X: batch_x, y: batch_y, keep_prob: 1.0})
        total_accuracy += (accuracy * batch_x.shape\[0\])
        total_loss += (loss * batch_x.shape\[0\])
    return total_loss / num_examples, total_accuracy / num_examples

In \[16\]:

\# Train Model
saver = tf.train.Saver()

EPOCHS = 60
BATCH_SIZE = 100

with tf.Session() as sess:
    sess.run(tf.global\_variables\_initializer())
    num_examples = len(X_train)
    
    print("Training...")
    print()
    for i in range(EPOCHS):
        X_training, y_training = shuffle(X\_train\_gray_norm, y\_train\_gray)
        for offset in range(0, num_examples, BATCH_SIZE):
            end = offset + BATCH_SIZE
            batch_x, batch_y = X_training\[offset:end\], y_training\[offset:end\]
            sess.run(training_operation, feed_dict={X: batch_x , y: batch_y , keep_prob: 0.5})
        
        validation_loss, validation_accuracy = evaluate(X\_valid\_gray_norm, y_valid)
        print("EPOCH {} ...".format(i+1))
        print("Validation loss = {:.3f}".format(validation_loss))
        print("Validation Acurracy = {:.3f}".format(validation_accuracy))
        print()
        
    \# Evaluate on the test data
    test_loss, test_acc = evaluate(X\_test\_gray_norm, y_test)
    print("Test loss = {:.3f}".format(test_loss))
    print("Test accuracy = {:.3f}".format(test_acc))

\#     try:
\#         saver
\#     except NameError:
    save_path = saver.save(sess, "./lenet.ckpt")
    print("Model saved in file: %s" % save_path)
            

Training...

EPOCH 1 ...
Validation loss = 0.735
Validation Acurracy = 0.810

EPOCH 2 ...
Validation loss = 0.431
Validation Acurracy = 0.891

EPOCH 3 ...
Validation loss = 0.375
Validation Acurracy = 0.901

EPOCH 4 ...
Validation loss = 0.346
Validation Acurracy = 0.906

EPOCH 5 ...
Validation loss = 0.273
Validation Acurracy = 0.931

EPOCH 6 ...
Validation loss = 0.309
Validation Acurracy = 0.922

EPOCH 7 ...
Validation loss = 0.287
Validation Acurracy = 0.934

EPOCH 8 ...
Validation loss = 0.310
Validation Acurracy = 0.925

EPOCH 9 ...
Validation loss = 0.280
Validation Acurracy = 0.934

EPOCH 10 ...
Validation loss = 0.307
Validation Acurracy = 0.929

EPOCH 11 ...
Validation loss = 0.331
Validation Acurracy = 0.925

EPOCH 12 ...
Validation loss = 0.268
Validation Acurracy = 0.932

EPOCH 13 ...
Validation loss = 0.286
Validation Acurracy = 0.939

EPOCH 14 ...
Validation loss = 0.307
Validation Acurracy = 0.934

EPOCH 15 ...
Validation loss = 0.258
Validation Acurracy = 0.937

EPOCH 16 ...
Validation loss = 0.299
Validation Acurracy = 0.936

EPOCH 17 ...
Validation loss = 0.301
Validation Acurracy = 0.941

EPOCH 18 ...
Validation loss = 0.309
Validation Acurracy = 0.943

EPOCH 19 ...
Validation loss = 0.246
Validation Acurracy = 0.942

EPOCH 20 ...
Validation loss = 0.284
Validation Acurracy = 0.944

EPOCH 21 ...
Validation loss = 0.341
Validation Acurracy = 0.941

EPOCH 22 ...
Validation loss = 0.287
Validation Acurracy = 0.941

EPOCH 23 ...
Validation loss = 0.364
Validation Acurracy = 0.941

EPOCH 24 ...
Validation loss = 0.409
Validation Acurracy = 0.940

EPOCH 25 ...
Validation loss = 0.416
Validation Acurracy = 0.928

EPOCH 26 ...
Validation loss = 0.375
Validation Acurracy = 0.940

EPOCH 27 ...
Validation loss = 0.342
Validation Acurracy = 0.947

EPOCH 28 ...
Validation loss = 0.313
Validation Acurracy = 0.948

EPOCH 29 ...
Validation loss = 0.408
Validation Acurracy = 0.940

EPOCH 30 ...
Validation loss = 0.367
Validation Acurracy = 0.941

EPOCH 31 ...
Validation loss = 0.396
Validation Acurracy = 0.937

EPOCH 32 ...
Validation loss = 0.369
Validation Acurracy = 0.945

EPOCH 33 ...
Validation loss = 0.381
Validation Acurracy = 0.949

EPOCH 34 ...
Validation loss = 0.324
Validation Acurracy = 0.944

EPOCH 35 ...
Validation loss = 0.289
Validation Acurracy = 0.949

EPOCH 36 ...
Validation loss = 0.349
Validation Acurracy = 0.951

EPOCH 37 ...
Validation loss = 0.309
Validation Acurracy = 0.950

EPOCH 38 ...
Validation loss = 0.308
Validation Acurracy = 0.950

EPOCH 39 ...
Validation loss = 0.317
Validation Acurracy = 0.953

EPOCH 40 ...
Validation loss = 0.313
Validation Acurracy = 0.953

EPOCH 41 ...
Validation loss = 0.361
Validation Acurracy = 0.949

EPOCH 42 ...
Validation loss = 0.389
Validation Acurracy = 0.952

EPOCH 43 ...
Validation loss = 0.404
Validation Acurracy = 0.948

EPOCH 44 ...
Validation loss = 0.337
Validation Acurracy = 0.945

EPOCH 45 ...
Validation loss = 0.426
Validation Acurracy = 0.945

EPOCH 46 ...
Validation loss = 0.443
Validation Acurracy = 0.944

EPOCH 47 ...
Validation loss = 0.393
Validation Acurracy = 0.948

EPOCH 48 ...
Validation loss = 0.378
Validation Acurracy = 0.957

EPOCH 49 ...
Validation loss = 0.368
Validation Acurracy = 0.954

EPOCH 50 ...
Validation loss = 0.437
Validation Acurracy = 0.946

EPOCH 51 ...
Validation loss = 0.348
Validation Acurracy = 0.955

EPOCH 52 ...
Validation loss = 0.431
Validation Acurracy = 0.950

EPOCH 53 ...
Validation loss = 0.369
Validation Acurracy = 0.954

EPOCH 54 ...
Validation loss = 0.439
Validation Acurracy = 0.947

EPOCH 55 ...
Validation loss = 0.440
Validation Acurracy = 0.949

EPOCH 56 ...
Validation loss = 0.447
Validation Acurracy = 0.951

EPOCH 57 ...
Validation loss = 0.338
Validation Acurracy = 0.955

EPOCH 58 ...
Validation loss = 0.465
Validation Acurracy = 0.942

EPOCH 59 ...
Validation loss = 0.416
Validation Acurracy = 0.957

EPOCH 60 ...
Validation loss = 0.403
Validation Acurracy = 0.958

Test loss = 0.614
Test accuracy = 0.947
Model saved in file: ./lenet.ckpt

Log[¶](#Log)
------------

*   Lenet 89.6%
    *   Preprocessing: grayscale, normalization
    *   batch size: 128
    *   epochs: 10
    *   rate: 0.001
*   LeNet_2 86.8%
    *   Conv.layer instead of FC
*   LeNet_3 92.7%
    *   flatten layer 2 to FC layer
*   LeNet_3 94.3%
    *   epochs: 60
*   LeNet_3 94.9%
    *   rate: 0.0009

In \[17\]:

import tensorflow as tf
saver2 = tf.train.Saver()
with tf.Session() as sess:
    sess.run(tf.global\_variables\_initializer())
    saver2.restore(sess, './lenet.ckpt')
    
    train_loss, train_acc = evaluate(X\_train\_gray_norm, y\_train\_gray)
    valid_loss, valid_acc = evaluate(X\_valid\_gray_norm, y_valid)
    test_loss, test_acc = evaluate(X\_test\_gray_norm, y_test)
    print("Train loss = {:.3f}".format(train_loss))
    print("Train accuracy = {:.3f}".format(train_acc))
    print("Valid loss = {:.3f}".format(valid_loss))
    print("Valid accuracy = {:.3f}".format(valid_acc))
    print("Test loss = {:.3f}".format(test_loss))
    print("Test accuracy = {:.3f}".format(test_acc))

Train loss = 0.000
Train accuracy = 1.000
Valid loss = 0.403
Valid accuracy = 0.958
Test loss = 0.614
Test accuracy = 0.947

* * *

Step 3: Test a Model on New Images[¶](#Step-3:-Test-a-Model-on-New-Images)
--------------------------------------------------------------------------

To give yourself more insight into how your model is working, download at least five pictures of German traffic signs from the web and use your model to predict the traffic sign type.

You may find `signnames.csv` useful as it contains mappings from the class id (integer) to the actual sign name.

### Load and Output the Images[¶](#Load-and-Output-the-Images)

In \[18\]:

\### Load the images and plot them here.
\### Feel free to use as many code cells as needed.
import matplotlib.pyplot as plt
import glob
import matplotlib.image as mpimg
import numpy as np
from PIL import Image
import cv2

\# img1 = cv2.imread('InternetImages/image3.jpg')
\# img1 = cv2.cvtColor(img1, cv2.COLOR_BGR2RGB)
\# img1 = cv2.resize(img1, (32,32))
\# plt.imshow(img1)
\# plt.show()

\# -------------------------------

fig, axs = plt.subplots(1,6, figsize=(10, 5))
axs = axs.ravel()

images = \[\]

for i, img in enumerate(glob.glob('InternetImages/*x.png')):
    imagen_BGR = cv2.imread(img)
    imagen_BGR = cv2.resize(imagen_BGR, (32,32))
    imagen_RGB = cv2.cvtColor(imagen_BGR, cv2.COLOR_BGR2RGB)
    axs\[i\].imshow(imagen_RGB)
    axs\[i\].axis('off')
    images.append(imagen_RGB)

plt.show()

images = np.asarray(images)
images_gray = np.sum(images/3, axis=3, keepdims=True)
images_norm = (images_gray - 128) / 128

plt.imshow(images_norm\[0\].squeeze(), cmap='gray')
plt.show()
print(images_norm.shape)

![](data:image/png;base64,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
)

![](data:image/png;base64,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
kEhh8hMSKf8PJbo2SRouaX4AAAAASUVORK5CYII=
)

(6, 32, 32, 1)

### Predict the Sign Type for Each Image[¶](#Predict-the-Sign-Type-for-Each-Image)

In \[19\]:

\### Run the predictions here and use the model to output the prediction for each image.
\### Make sure to pre-process the images with the same pre-processing pipeline used earlier.
\### Feel free to use as many code cells as needed.

import tensorflow as tf
import pandas as pd

labels = \[1, 18, 11, 25, 3, 38\]

softmax_logits = tf.nn.softmax(logits)
top_k = tf.nn.top_k(softmax_logits, k=1)

with tf.Session() as sess:
    sess.run(tf.global\_variables\_initializer())
    saver2.restore(sess, './lenet.ckpt')
    
    my\_top\_k = sess.run(top_k, feed_dict={X: images_norm, keep_prob:1.0})

names = pd.read_csv('signnames.csv')
\# ClassId and SignName
fig, axs = plt.subplots(len(images),1, figsize=(20,20))
axs = axs.ravel()

for i, img in enumerate(images_norm):
    axs\[i\].axis('off')
    axs\[i\].imshow(img.squeeze(), cmap='gray')
    axs\[i\].set_title(names\['SignName'\]\[my\_top\_k\[1\]\[i\]\]) 

![](data:image/png;base64,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
u1Zsz5w5Mytjrelh3YNtt93W1bbGBqV51wjxBmpJsxBCtHvkLIQQLuQshBAu5AJiCngAAAHCSURB
VCyEEC6qXuC0grKsoBtL+CvjDUDyBn15sdo7bdq0iu3HH388K2NltY4YMSKzWddgvS8sMdMSG++4
446K7X322ScrY00zaJ3T6jdrqj1vAJpHqPRmJVtI4BRCtHvkLIQQLuQshBAu5CyEEC6qXuBctmxZ
doFXX311Vq53796ZrSx6WiKaJbZZopxXNLOOtSIny9PSWSKoFZm5fPnyzHbBBRdkNqu+Aw44ILPt
uOOOme3dd9+t2N5///2zMtZUe1bE6XHHHZfZrH6z+qixWbeK4LTRyEII4ULOQgjhQs5CCOFCzkII
4aJdLox8+umnZ7bHHnsss9XU1FRsW6JcU6au84pyVrmyzVpk2UqVnz59emazhEVLaD322GNdbSsL
mt4p76xzekVgi6YIlZ662hsaWQghXMhZCCFcyFkIIVzIWQghXFR9BKcQonnQyEII4ULOQgjhQs5C
COFCzkII4ULOQgjhQs5CCOFCzkII4ULOQgjhQs5CCOFCzkII4ULOQgjhQs5CCOFCzkII4ULOQgjh
Qs5CCOFCzkII4ULOQgjhQs5CCOFCzkII4ULOQgjhQs5CCOFCzkII4ULOQgjh4v8DzTwP38yLweUA
AAAASUVORK5CYII=
)

### Analyze Performance[¶](#Analyze-Performance)

In \[22\]:

\### Calculate the accuracy for these 5 new images. 
\### For example, if the model predicted 1 out of 5 signs correctly, it's 20% accurate on these new images.

import tensorflow as tf
saver2 = tf.train.Saver()

with tf.Session() as sess:
    sess.run(tf.global\_variables\_initializer())
    saver2.restore(sess, './lenet.ckpt')
    
    test_loss, test_acc = evaluate(images_norm, labels)
    print("Test loss = {:.3f}".format(test_loss))
    print("Test accuracy = {:.3f}".format(test_acc))

Test loss = 0.000
Test accuracy = 1.000

### Output Top 5 Softmax Probabilities For Each Image Found on the Web[¶](#Output-Top-5-Softmax-Probabilities-For-Each-Image-Found-on-the-Web)

For each of the new images, print out the model's softmax probabilities to show the **certainty** of the model's predictions (limit the output to the top 5 probabilities for each image). [`tf.nn.top_k`](https://www.tensorflow.org/versions/r0.12/api_docs/python/nn.html#top_k) could prove helpful here.

The example below demonstrates how tf.nn.top_k can be used to find the top k predictions for each image.

`tf.nn.top_k` will return the values and indices (class ids) of the top k predictions. So if k=3, for each sign, it'll return the 3 largest probabilities (out of a possible 43) and the correspoding class ids.

Take this numpy array as an example. The values in the array represent predictions. The array contains softmax probabilities for five candidate images with six possible classes. `tf.nn.top_k` is used to choose the three classes with the highest probability:

    # (5, 6) array
    a = np.array([[ 0.24879643,  0.07032244,  0.12641572,  0.34763842,  0.07893497,
             0.12789202],
           [ 0.28086119,  0.27569815,  0.08594638,  0.0178669 ,  0.18063401,
             0.15899337],
           [ 0.26076848,  0.23664738,  0.08020603,  0.07001922,  0.1134371 ,
             0.23892179],
           [ 0.11943333,  0.29198961,  0.02605103,  0.26234032,  0.1351348 ,
             0.16505091],
           [ 0.09561176,  0.34396535,  0.0643941 ,  0.16240774,  0.24206137,
             0.09155967]])

Running it through `sess.run(tf.nn.top_k(tf.constant(a), k=3))` produces:

    TopKV2(values=array([[ 0.34763842,  0.24879643,  0.12789202],
           [ 0.28086119,  0.27569815,  0.18063401],
           [ 0.26076848,  0.23892179,  0.23664738],
           [ 0.29198961,  0.26234032,  0.16505091],
           [ 0.34396535,  0.24206137,  0.16240774]]), indices=array([[3, 0, 5],
           [0, 1, 4],
           [0, 5, 1],
           [1, 3, 5],
           [1, 4, 3]], dtype=int32))

Looking just at the first row we get `[ 0.34763842, 0.24879643, 0.12789202]`, you can confirm these are the 3 largest probabilities in `a`. You'll also notice `[3, 0, 5]` are the corresponding indices.

In \[23\]:

\### Print out the top five softmax probabilities for the predictions on the German traffic sign images found on the web. 
\### Feel free to use as many code cells as needed.

import cv2
softmax_logits = tf.nn.softmax(logits)
top_k = tf.nn.top_k(softmax_logits, k=5)

with tf.Session() as sess:
    sess.run(tf.global\_variables\_initializer())
    saver.restore(sess, './lenet.ckpt')
    my\_softmax\_logits = sess.run(softmax_logits, feed_dict={X: images_norm, keep_prob: 1.0})
    my\_top\_k = sess.run(top_k, feed_dict={X: images_norm, keep_prob:1.0})
    
    fig, axs = plt.subplots(len(images_norm),6, figsize=(15, 15))
    fig.subplots_adjust(hspace = .4, wspace=.2)
    axs = axs.ravel()

    for i, image in enumerate(images):
        axs\[6*i\].axis('off')
        axs\[6*i\].imshow(image)
        axs\[6*i\].set_title('input')
        guess1 = my\_top\_k\[1\]\[i\]\[0\]
        index1 = np.argwhere(y\_train\_gray == guess1)\[0\]
        axs\[6*i+1\].axis('off')
        axs\[6*i+1\].imshow(X\_train\_gray_norm\[index1\].squeeze(), cmap='gray')
        axs\[6*i+1\].set_title('top guess: {} ({:.0f}%)'.format(guess1, 100*my\_top\_k\[0\]\[i\]\[0\]))
        guess2 = my\_top\_k\[1\]\[i\]\[1\]
        index2 = np.argwhere(y\_train\_gray == guess2)\[0\]
        axs\[6*i+2\].axis('off')
        axs\[6*i+2\].imshow(X\_train\_gray_norm\[index2\].squeeze(), cmap='gray')
        axs\[6*i+2\].set_title('2nd guess: {} ({:.0f}%)'.format(guess2, 100*my\_top\_k\[0\]\[i\]\[1\]))
        guess3 = my\_top\_k\[1\]\[i\]\[2\]
        index3 = np.argwhere(y\_train\_gray == guess3)\[0\]
        axs\[6*i+3\].axis('off')
        axs\[6*i+3\].imshow(X\_train\_gray_norm\[index3\].squeeze(), cmap='gray')
        axs\[6*i+3\].set_title('3rd guess: {} ({:.0f}%)'.format(guess3, 100*my\_top\_k\[0\]\[i\]\[2\]))
        
        guess4 = my\_top\_k\[1\]\[i\]\[3\]
        index4 = np.argwhere(y\_train\_gray == guess4)\[0\]
        axs\[6*i+4\].axis('off')
        axs\[6*i+4\].imshow(X\_train\_gray_norm\[index4\].squeeze(), cmap='gray')
        axs\[6*i+4\].set_title('top guess: {} ({:.0f}%)'.format(guess4, 100*my\_top\_k\[0\]\[i\]\[3\]))
        
        guess5 = my\_top\_k\[1\]\[i\]\[4\]
        index5 = np.argwhere(y\_train\_gray == guess5)\[0\]
        axs\[6*i+5\].axis('off')
        axs\[6*i+5\].imshow(X\_train\_gray_norm\[index5\].squeeze(), cmap='gray')
        axs\[6*i+5\].set_title('top guess: {} ({:.0f}%)'.format(guess5, 100*my\_top\_k\[0\]\[i\]\[4\]))

![](data:image/png;base64,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
Vj3eH6o086NRs5+bcn8g6eYY40JVUYugjqAAACAASURBVMDJrXY+TdXk6lFOlfTzWMnkxpQQwp4h
hDeGEHZutccZqmQ59lzItyS9NVQp9Keokpy0pfVyeYMqP5sQqsx6nMd7typFxW+1xryPqfohZJR/
lfSJEMIBrfrOCCGc3bLb+kfTGNVBe7xE1Xjx2lhl++O5jE60f3eo0iXvpuqaafvQEas5E/eoSgAz
yvmSPtgal2eqGuO/YuowSVVUbTTl8lJJp7auuxOV+84pkn7cybl1Eb+PqaP72PmSfr913eyuyte/
0m5frR+HLlE+7myxfOvl5DOqoiAjqnznpJbvnCL3HdIvvrNaVZTu6Na/0R93jlWbZ6Se8p24g7Kv
9MI/5dkImXlltp6dqWU068tTquZzTMH2f64q28oDqvStdTYqVQ+fC1vlvrejz7lX/6l6qL+/1U4f
an12TqvNV6s1P8D0XbFPzL7HqZKhPNG6aD6g6mEktL4/SNWFulbVRNB/Mf5wfOv4T6qKgvxI1a9I
+yhl2xnNFjSvVebvVP0CtVZVIglm3fqxpD8r1PUUVQ8sa1rHu0LSi7fQdtdLOh5/f6Xlg/z3Vnz/
5lZbr1MlB5yG76apmnexrrXNm9sc7zJzvPmtfnhcVTrv0c//p1rZ9MbAfw5oneeGVpuP/hvNjHSq
mjO9zZD0Q3WejfCtrfYZzUb4kKSTW99NUnXTe1rVL/of0LOzEX5DlXR5laqX0dF6XKAqW+JaVb/A
vbr1+ZtURXvWqbop/4vS+PRnqhIHbEu7/LaqXyPXqvLtiyQd1XDe41vnPROfHSPpRlUJO26SdIwp
M13VxOOp+Ozc1vkvk3QaPv+RpFeNhc+0ObcZqq63p1p9d5ukd+D7Z/lQ6/OPts6lk2yEc1TNQVoj
6VJVv5p+0fjVipYPfEjPzkb4wZYfrFE1rvxNk3+oeYya1er3WYW6XqYq4ku/+TG+P7q1v1Wqrv3/
VCFramv7P5T0OfwdVI2TT7b+/Z2Q1bK1zccl/U/8vauqSferVSUbGWx9fpyql/kx9xtTX7+Pxc7u
Yy1fflTVtfZlNWQglfRbMmPclsqruhY/Y9rvwtZ5/lTVvFK1zv9BSRPcd/rDd7DtbDVkI+wl3xlt
aKeBEMIySX8QY7xkR9fFqdiePgnVoq7/GmM84Dmv2A4ghHC6pPfEGDvOMNRtQrW21i2qBslSJsVf
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
dL1xeyvPLKVLZ9uWUnxLuWSttDwEfYS+IOX3a55zJxJ0u00prT3rzPO1Ukl+129jz6GHHlrbxxxz
TG3vtdde2XZWgr4leK9ZsmRJ9t1tt91W23w+2XfffWubfc/U6ZJ099131zYlik888URtUwq/bNmy
rDyX4CmNMSWfsPej0rId/JzLv9jlW/h8YL/bWjyy5TiO4ziO4ziO0wX8ZctxHMdxHMdxHKcLjKmM
8KePpTDeUxGHHslXiZ46kkKim5XCfRuRNXAgphDyOGQmDDGXdowbSBKGPXdPEorDdksSoZm7pXpN
n5pLK6aEJEUbtzFJ1gYRqR6cgEw6ysPUa6ckmddjIckrlm1Inz+4MYVKH16XzmvdhjxUOggZpQIk
AAEylxGE0zfn0gBFht37KzsYZQmURVjJQCkLGMtQHkZZj5V1MFROaQz3e9hhh9X2HnvskZVnVh7a
zPZDiY2V3zBsTikEyzAcznpZeSHPk9JLHoOSQivPbMqa2A+U5IEW+hNt9g3bktKEAw44INvXJz7x
idr+2te+VtuUUFCmYLMwcbuSjPaBBx6o7QsvvDArz/68/vrra3vp0qW1zeuFEjPLnnvuWdsPPfRQ
bZcygllZE6+tfstmWfIJK2XhNce+pNyJZXiNWUlfKVNhaeyy0jv+PXv27LY2fZoyaSkfrwjPi1Ik
nrv1I/oCZUHcF/3QtgUlUv0mA5PKY3xT1sbS/Y6wzex9kD7XiSSV2QelvM3pp6wXpYb2fsN+pm+V
siyWpLpSWcJdGoetj5Skk/3A8ccfX9s2AyFhW9DHSlJhypyPOOKI7Dte13fccUdt33LLLbXNDIS8
B0m5j5TkpLwf8H4m5bI+yigXLFhQ289//vNrm88wVkbI41AGSPn8DTfcUNuPPPJIVr703LYteGTL
cRzHcRzHcRynC/jLluM4juM4juM4ThcYUxlhnDq3tieFFKYejrnsYBNUJgEywAnIYBghPdyoFIac
Mj5JXCTpmOmpzIKdU3h1/4hF9zZj8dunc4nLAGSJYRNkZhuRCWgjMiwN59KScQEZexBq3wuSyNkT
U0j3biy2vHwwz/Dz8FrIFdF+g1g4efxAqmNQfi4bB1N3R/VXOJ1ShqZF70rSilIGwpLUUMrD9szs
RlkEw8zf+973svKUW5XkP8TKShjqp2SD8jLKP0oZ96S8LRja5/lTOmIlUqXsP/0C27/TBZpLC9CW
Fkg+99xzs/Knn356bbP/mE2S9bKLRnJBSUr/COvChYulXPqXLXxeOOcmeSWlHiUpEqVDNlMfj9lv
CxxTItU0XpSydJay7jXJfdhG9LFS31kZF8eF6dOn1/b9999f25SZMnOmlMuE2Pc8F/oUM41ZP+Jx
eJ5sL449TX64tVnXegH2ZVPWxaaFoUcp3fusdK4k0aPPUq5nswmWJF+sIz/n+Cbl/sf7TQnWxbYL
61y6d7O+9l7Vb7JlQgklZWz2/s7tli9f3vZzLpDMdrRZ9phB8MYbb6xtSt5ZF9u+nYz19Akr3aOM
kZkOFy5cWNvnnHNObZ988sm1TUmhlF8vLH/rrbfWNrMhMhOilI9925uF2SNbjuM4juM4juM4XcBf
thzHcRzHcRzHcbrAmMoIhzcnCcFgJpvIQ+AR2fXiEKRgwylsPQgZ3IwpKex47AH5++Phk1O4ctrT
SRqxeW0KiQ6FdPzhiXlGuOHBFJYcUgqVbx7EuYxDVqiRPLPK5hGE7ddikdSRVK/9xic5xi6TsTDm
TnlWnomDSY6xbHU65jCkipsQco+mXcMAMj7F/gqtU3rVlBmPMgeGkCmToHyHEgW7UOCRRx5Z2wxB
X3TRRbXNBfys/KUkbSgtwGjlFo8//nhtUybE7D/7779/bVNeaOU2lPwQG3YfxcoUKBlpknH2KpQA
sJ/t+VP+wkxMlItyX+wXm9Ht0ksvbbtfHp+SD+t/9Ae2f0nWRimXlEtISgvTluS1tv95zvyO+6L/
26xfpeP0GyUZk1ReZLUTeaFtE/YxbbY9j2Gv9zlz5tQ2ZUH33XdfbR900EG1bTNpcrvSwqCsM33P
+g5lhKQkgbbtRd/vRzkzfZ/XiL2P0Z84xpbGW/qFlRF2IuWi9M/6D6VlrD/HlFJ9bd3Y/yVJH4/R
JIksjV1NC3SXMvb2AxdccEFtc0y1Emb6Eu/1fNbhNc52uO6667J9XX755bXNZxC2I8c6ew8tSU1L
/Wj7hMfhfZf3wy996Uu1zfHtxBNPzPbF641jFKWKPBcr5WddPBuh4ziO4ziO4zhOD+IvW47jOI7j
OI7jOF1gTGWEA8jAB3WdBmQXKkR2v0FkWRpJGen2npSyhpySEsXp0JEkD5SkgUfTdpuw4O/6AWSC
mpJCh0OT8pDoxglJ6rAJ2QE3K5UfH1N4dPxQCrtK0qY1CMevQqYTKM4mr02hyj3XJ6nj4NQ8vDpu
Z2TlGU5h/2XrsNDfuFTfwWikKZAOxoawey9SWnzYZuFiSLgkGWBofe7cuW1tSbryyitr+7vf/W5t
U9JYyngo5dIMSsQo32gKUzPUzaw4zMzIDHT8/MADD8z2RfkHt6PkoCQptJSyKfYylFlQUmr77MEH
H6xtyhZKi66y/88///xsX5SbcvHrU045pbbZL3ZR7DvvvLNtPefNm1fb9BFmmpNy36LPcdFIwmPY
Ra1LUjLKWUoSN1um36Q8rG/JJ6T8nNmWlL5xTChtb49ZWsiX7U05sZSPg8xkyX5ktlRKCu3fzExY
ylLHc7RSHPo4r0O2Jcdxu6htk1ytHygtqG6ltvy7JNcs+UKn1xvrMm3atLbHkHI/4XYcO0sSLyn3
Z95vuR2P0SQtLi1YXLpGbBuxbfptUeyvfvWrtd2UCZXXGL+jhJPTDOiHlAxLuYSU/cLszLyf2fsW
y1Pix0x/TTLC0sLTfD7i2MNxkGOalN/32Pe8b7K9mq6j7fUdj2w5juM4juM4juN0AX/ZchzHcRzH
cRzH6QL+suU4juM4juM4jtMFxnTOlhRgxbZ29Te0y0gDv8tOqbpH7Z+0xwcPpDk0Oz+WbEnaFNMx
n5yQ9MZrp81Kx5ic5jkNj8/Tsa6L6ZjDSrryENh06fOJU2aJTNkVaaKnpRW81zyUtKxPP5rSP+8x
nLSkU9cnXaokzRqAdn1aml/0FOq4cijp3W1298kRKZvVX3O2qOmnptemCS7NLaFWnPOnjjvuuNq+
4oorsn2V5mlRg865UaeffnpW/uCDD267XSkVrtW933vvvbV97bXX1jZXP2fqcOqVraabaV9LcwhY
F5sqnm1eSuXcy/D8qV3nHC0pbzfq4KkLp19R493UZtS+H3vssbU9a1YaLxYvXpyVpy6d9T/rrLNq
+7bbbqttzq2R8jkVLM95FytXpjmunHdjU2xzrkxTCuJRmuZg9NucLZ4L51zZc2R/lea1sR05R9LO
U+K+WYb+tueee9Y2fUrK+5XlOXbxGNxeyv2SY8yyZctqu3St2DkXPD6345jONPC2XTlXo998RyrP
v7JLhfDc7FzkUdj/TenO+R33xflX9Dm7bAX9/HnPe15tz5iRnmGWLFlS25xfKuXjJY/P/XJeaNN8
mNL8ntIYY32k3+ZpEd7TS8vHSOVlZthfpTlLvE9IeftNnz69tvmsNHv27Nq2c7i5ZArnabG/OHY0
3StKSz1wTOEcZPs8SH/jMTmvjM9d9hnsuVymxCNbjuM4juM4juM4XcBfthzHcRzHcRzHcbrAmMoI
rVhwlIFgvkEUeGQkhdoP3T/JX+aMS2HvsCpJINaGXI7x1PgUNn9m2r5pu12TBCNMStKKoZE8DLlx
Yzr++JBkIhMHUxhzYCDVa8XKXBqwYW1KBT9zryQb2f3gI1O9xqdQ6SMr7q7tGZtSum9JmrouhWT3
nZLCw7OmpvqvfCzVMQzkUoSBiHfrPkv9zrSjDCFTuiPl0gR+R5kK5X233HJLbV966aXZvijLYgrR
BQsW1Pa73vWu2j7mmGOy8pTsEIbGmSLXSgMoDTrhhBNq+5e//GVt/+xnP6vtX/3qV7XN8L09zt57
713bpfTNFrYrZWj9An3mgQceqG0roaAMgW1DaQXlN5RkWjkF98XU/dwvfeyRRx7JylNy9epXv7q2
TzrppLbHuOmmm7LylL7y+LyW6HOUNfG8LPSFkvSwKZ1vk/ypF6EMiudo5Uml64f+Qh9hO9rU7yXp
IT8//PDDa9u26RNPPFHblAKddtpptc20zJSjSrnE0Y5ro1CKxHO0MkJKcUoyQPqeHTcpBbLjfT9A
GWRT6vqSb7FvO5VR0p94vdNmW9o+4z2SS03wPsj6Pv54vuQNpV30jVJflmTaUtl/Sm1k4TVTkj33
Kjz3pjGU58W+Z3vzHsD+stcUnw/mz59f21wOgn68cOHCrDwlyewvO8aVYL+WlkMg3MZK6Xn+HMc5
dvFZycoQS0sYbAv95XmO4ziO4ziO4zh9gr9sOY7jOI7jOI7jdIExlRGOH58ON4L3vBBNZhUIDvfe
PX13xJQUjp/52P2pwMaUBezBnZJkQpLW7TknHWdCkg6OG0x1+cUvrk7bjLdSrqPTd5tSiHFwIIXQ
f/rDi2r74kuSxEuSNm5K4cqZB86u7Te+8dzaPnLfI9L2kDUNrTKyIqXznLAmZamZOTVJPnYbn0Kl
G5VkSJKkkXTOfRZNz0LApRXppTyczvA4ZTEMR9988821baUQDEGfeOKJtf22t72tto8+OvkHpTu2
bswCRVkP5RNLly7NylPiWMrc9eIXv7i2mWHHZrajrIPnxbpQOkYJm5TLAZokZr0KM6rRf6z0j3Km
koSB0o6mDH6lzGGULlI6aOUclPJQysXMYZQ5zJmTxjopl3PwmJSJUFbEPrdZmFhP9n8pS6il0yxq
vYiVloxiJV0ce0pyJ7YdpTi2vUuZu/bYY4/aPuyww2r7/vtxPzTHp+yUmSyvu+662qa0VsrlOJQP
0WYmT/qOzazI+tNHeL3wOrTXJMvY8b7fYFs0ScG2Nuui3Rf7gPc+wra00vBDDjmktpn1kn3GrK77
7bdfVp7jDcc1jhe8FniN2WuB59Yk4y19bv2xn2C7NI2bPEf2JctQRsj9Uhoq5dknDz300Nredddd
a5sSdWZ3tvtjX9IP+KxkM2GynqVsgOxjXiulsbqpfFNmxG2RQZbos0dux3Ecx3Ecx3Gc/sBfthzH
cRzHcRzHcbrAGC9qjEXZIMML0chvsPju3OkpjLfPxiSVmLo2hSFXD6ZQ6YapuYxw7aQU+tx5Qgqn
P7o0Zf37+he+WNtvOPfNWfldxqcym7HY8pWXX1nbP/xhygh3ztmvysrvs3eS6VzwX2mR3G9d+N+1
fdi731nb02ekxYqHnk6ySUmKw0l2MnFjkidOG0jSp+lTkkTq/qfzkGoch3B6g+SnF6HkgeFsK7co
ZddjGYawmZHLSlTmzk19QfnNEUck2Sfled/+9rez8gztv/zlL69tyifuu+++2j7//POz8tdff31t
M7xN6SJD/kcemTJc2ix7XByR33HxUko8rPSE21GG1i+UMl81Qf+h1IAShNJiklJ5MVlKHUryPCmX
cHA77ouSESsjvOuuu9qW5/G52DE/twuuMnNeSV7ZJOHoN+kgKWX6sufL/mff099YvkmWUpIe8trn
eMXsWlI+dlFqzGuX0lQuRCpJP//5z2ub4yWlYzw+F/S2siBKVdlGJYmQ9RUeh37YL5TGCCt3Ky3e
W7p2mrLs8X7HMYL9xP3asYNy0dKC1ZSL2fIcbyhxpc/Tr5mx0bZLJ4sSN7UF699vi2J3eo3Qr3gf
532v1PdWBjhz5sza5nMA+4uLGlsJKSlJgDle2ekTXCybUzs4jpZk2lbKzvMvZX5me9nxhb7UlK25
Ezyy5TiO4ziO4ziO0wX8ZctxHMdxHMdxHKcLjKmMcCBASsOsPMN5eG7alBT623dSCkcPPpayH60K
qeorp6ZsOZqUhzTHbUpSrk1TUojxJ1dcko4xKy12fPLJKeucJG1an0KvA5A+3rwwSbzmHZUWlzzz
7Ndm5acMpHDniofT4mk/+GlaQPfRdUl2MbhXWqx488o8Q9AELJA8blNqo8kbU3h2j4lJJvLgQB5+
H2ZItL+i6ZmsiaFtu0gkQ807MNF13wAAIABJREFU7bRTbTOczEX4mLGN20vS6aefXtuUDjK0f8UV
V9T23XcnaaokveAFL6htSmkYqv7hD39Y21bG+OY3J0krJUtcgJT1Z/a6Aw88MNsXZR3MWkhpQVNm
Pda5E1lHL9O0GGZpYd7SwqKlTFlSLk+g/9BH6b+UZki5NIdSmP3337+2mUWOmSVtecox2P8sQ7kP
t5Hyc2b9bdbKdttb+k1SWJJH2ixnHBf4Xel82Ub0FSkfi5iBkNc1Jci2Lly8mJJCymw4Jh1//PFZ
ecoKOXZwgVvW5d57761typCk/DxLi/qWJHRSeYHnfmFbFvTmdqXMabSt/1Dix+PzPsgsg7x3SLnP
kVI2ScpLpdw3ShlXKUujbaVgTTKxUZqyPJYye/YDJfm6PUf2P7/jWF0ax+xYz2cK+hGvSz6rcFFg
KZeEsl+ZRZkZke2zCq9x2ryH0Q9KkkIpP2faHC8py7fXEbez320t/eV5juM4juM4juM4fYK/bDmO
4ziO4ziO43QBf9lyHMdxHMdxHMfpAmM6Z2tQ0N4Kumyj0d5tSqrWrph3NLgJqYmhZd04JenbNxtd
5aSB9PfSJSnFJOftvO13f7e2p02blpVn2ts4wlWrk2Z0552S5nPTxjQHRpJCSHrhMC5paYeUPl+P
fQ1NSvsKZg5I3IzVxMcjLTXacsqkpDEdjEkfLUmD2G5goL/mTTB9LTXGNlUn9crUOzPVKFc/p/aY
abClPPU254lx/hjnT9n5K4ccckjb8tQ4U8NuU7AylTvn6VAT/eijj9b2jBlpvh/TOkvSLbfcUtvU
ZNPmeVl9N78r6eZ7mZJfWB02t2MbUBdOHXdJUy/l/bnvvmle6IMPprmn9JmjjjoqK8925nxAptZm
vex8BKZv5hIHHNNYhssILF68ONtXKW0v/YLnX5rLJZXTGfcq7G/2iZ0nRUqpmGmzHew8Je772GOP
rW22/Zo1a2p7wYIFWXnOwWJflOZt2PmCxx13XG1zXinHTpbhWGfnYNCXOF5zPgbP3/pO05IC/UaT
75fSwtNmO3F73h+lfE4MfYbpr5vm+NLPuWwI7zdML897j5SnA+fcMI59PEZpaQyp3BaluWxNc2v6
bc5WaS6jnR/Mv0tz9Oh7bGM+A0j5vYLtxeVf+AzGuaOStHz58nankvnIYYcdVtv0DylfnoL3Ovox
x46SH0h5m/Gc7TIrpfKlZTu2hf7yPMdxHMdxHMdxnD7BX7Ycx3Ecx3Ecx3G6wBinfocEAyG5QZNJ
etfJ6bsJCINOGELqSZTZBOncenNGU0MKr157eUrTPYDQ48qVKTR+5ZVXZuWZspmhWso84ghSi44k
WY0kRZzcyDiENAPSeI6HtGQkvf9ONO/CgzjO8AhTX0JeGCB3GjTlKUfoLxVhFsJlCNlKThhCZ/pk
Su9YnrIxpiaVnp3OdhSGzRctWlTbTKUs5eH5FStW1DZD8Dy+TedaWr2cvscwN+UTlK1JeYrvkhSJ
aeC5X/tdv8t6mtK1s22bUsqOQr+0EoT58+fXdkmGSamfTd1+55131jZlQkuXJjk0j28l0PR/yoSe
fPLJ2uZ1Qbka/VXKZdf0jVK6cyuXYlv2m4yQdWffsU+l3K9KfsHPaVPuI+X9TZsSH37+kpe8JCvP
9Ou8Xtl3N910U23bZSsoA6Pv3HXXXbVN/6KkzMqION6UJMg8F3tNsm2alhToVToZR6TOUsSzPP2H
7S/lbcY+5z2NfWyvSY4911xzTW0vWbKktiltf9GLXpSVZ3/ymLwnllJxW3kut+M5d5ISX+q/8YaU
Upw3wXbhuXNf3MaOPf+PvTcPs6u4zr3fOt0tiUEYIyEJCSQBAoEEiFnggcEYTOJ4jPGc6ymJHSfx
F+fL4AxfBmfOTe7NdeIkznUGz8axYye2iR0HYwYzmEFinjWDBAgxSAIkdZ/9/bFPV/1q0bU5Qjrd
fWD9nkePVp+zaw+1166996m33qJslPXNnOSzjpWQ8vmG9xFKkHmO7TMc/2YbU5LxNU0NwH3md3wG
LMkrpe6mregW79lyHMdxHMdxHMfpAf6y5TiO4ziO4ziO0wPGVUY4ZWrqOnwGveQDA3n36D4wkxkY
Tl3ggV2iSgu1B9N6B/dJLjyStHFdmr18xQ3XxXj/6al78tpr0+d0y5Gk17/+9TF+85vfrLEYGUn7
RUlhfQAIp6Tqboexuz7DMNwXba8x3RDRPTrMmJu2EinszIj6S0fIY2FsJQMlmQbdjtjNzeXp4GTh
7OU//OEPY0xZxLp167IylNOcd955MaYLFLvwbRc4HeB4nOyCt1KmUazbDrvmWX+UmDC2ucPt96Ms
o+ToZeuvVAcsQ2kCP6ckUModl2655ZYY81wwFyjrkvJzSMkOpRXMEesqRVkppWCUwdIdjsvTzU7K
c946gI7C/LXXZZPMZ7JTkpzYtoYyFy7HmOee1zHbJymXdNK9lPlJ6daJJ56YlS/lKN29LrvsshhT
HihJ7373u8fcF94fN21K91bKiuyxlNpk5gH30cqaeI3a7/qZklRQKkvGmGOscyvF4nlme0EHSco7
m9oelqfUmeeZ0mYpbzt5nJQ70tmwtD0pl3YxLtVfk1tuvznplqR/9tibhiOMVb4US/k1Zp+HR6FM
ueTsZ/eFQxH4DMZ7mJTnWMlZslQv9lhKkspupb1kT597+uuu5ziO4ziO4ziO0yf4y5bjOI7jOI7j
OE4PGFcZYdWCjA4T7FbKu8wHMJFxhUmB21XqOhzAe+LACJzaWnm34w+uSA6EmpKW+/mf//kYH3JI
6hL91Kc+lZW/+uqrY3z++edrLPLJ5vLtt6skQRmkFA4ywoFdSRoydVc6rrDLdHkPpu7aYbgsVkPp
82cqTMrazrtHB1qU3/WXqxPrmN3OVgbGLm12+9J1rSRFsRIDrpsyQrr1UG5F9zlb/pprrokxZUl0
A7TyKpanLIOSEcqKWC9WSlCS0RGWsVIgbrMfZYQlGWBTPZVkBzxPLM+JXaVcgsFzzuUoC1qxYkVW
nnnKSamPPPLIGC9atCjGnDhbynODEyxTSsQJZ5ljr3nNa7J1ffWrX40xZW2kqV6tLLWfsM6co9j2
onSMJQkuc41yUil3c6OjFx0nTz/99BhbaSf3hdcypWNNk+KyvaJcjc5ydDDkPloXV7bJrMuSy6Ot
79JEyP0Ir4sm+VLpWuJ5onuubZP5N693TkzL+xjdB6W8LaHbHO8DbJ/uu+++rDzzjG0UJWKUkvG8
Wtc5brN0H+M11q0jXT9Qutc01VGpHerWzZB1xOcmSkXpLGifW/gcUqpvykGb9qskOS85EHYrUS+1
PfaaLE0q/Xzwni3HcRzHcRzHcZwe4C9bjuM4juM4juM4PWBcZYQjkPiNQBJYmVe+0Epd4DurXVgu
dfENDacu1Sm74Mb3TN6dvmrtmhgfuiS5hR2+KMVTsF/scpeku+9O3eu5FCkts21r6jadMjWXY4RW
6h5nt3kLDob74fiHnsbku8/kcophYbI/SAqrodSF/ORTqb6GW8ZdjxLL0F+uTpTbsWu7yRGM8pmS
6xqhW46UOzpx+1zXOeecE+Ozzz47K//oo4/GmG5P3D4lNnb7pe547gslN6yXJkliaTJJukDZLnMu
149SnpJjkZVclKQCJXetOXPmxNhKsSjTYd0ef/zxMW6SzxA6DTLmZMN2Um3KWinlYUz5F2VhVmrL
a4l10e3Eosz5fpPylNy97DGWnNJYd8wvOrMdd9xx2bro1Mb6OuOMM2K8fv36GF9yySVZebrosr2g
qyQnZLeTGlPWuHjx4jH3mTHzyEqQDzzwwBjzuAjrzkoi2Q7244TqpbanSZbEtoDXDuuSn1PmLuUy
wCVLlsSYExlz+yeddFJWnhOfUyLIZxi691LSKEkzZsyIMWWIbCO5rtJEulIukSs5EzbJ0rpx6pus
lGRx9hmGf5cmTi/JmZvqqzQZvX1WKZVnXHL3tbC9K7m6dks3E80T64TJMnsqhfeeLcdxHMdxHMdx
nB7gL1uO4ziO4ziO4zg9wF+2HMdxHMdxHMdxesC4jtna1YZ1O+SPrVau4d+lpD+tQtJQjnB8Dtf1
VBqPMkW5Jnf//ZN2+aG162L88KY07qE9kvSj1//o+qz8/EMXxPiglyTb3SMWpnEP//4f/x7jz332
n7Py06FRvuQ/vxfj05efFuPDZqSxFu370hixadvzMVttnK2n90vrfbyVxtNsezrVy1RjQ99qQYur
/tIuczwStbt2nAw17RwPQ9039eybNm2KMXXjkrRq1aoY0zqbWnWOVeA0AVI+tobboXX3YYcdFuPr
r89z77bbbovx3XffHWOO0ylZOVMPb5fjOC/WC3Xf/FzKNdZWn98PlMZDNenVOU6NYwJYT6edlq5j
jr+T8rEKtMPmuFCe12OOOSYrf8opp8SYNvIca7NmzZoY2/xdsCC1XTzOWbNmjbmPt9xyS4ztGB5a
jvMa47jGJitrXjMs0w+Uxqg12QSz7eHnHM/E823XxTqaN29ejM8777wY89zbsSi0bmfdn3vuuTFm
O/TpT386K8/vaDHPsQ5c75VXXhljtnVSbjfO/eS4j9LUHlJ/TjVBSmMU7biR0ngijiPhvYvjKm3+
HH744THmueS1y3Fedrwn7xHcf479bRpzyDaGy7GNZI5zOgl7vtne8los7aOtx27t9icjpbFNduwi
c6Gb8VulKSikvC5LbR9pGgfXTd3bz0tj8Z7PueMxl8addzuVEPP4+eA9W47jOI7jOI7jOD3AX7Yc
x3Ecx3Ecx3F6wLjKCFut1CU6INgvK+8SffxpdIPuOzd9MbgmxbSf3pq6oIeq3JLy7POSHfc//s3f
xfj3fvd3Ysyu2mmDuRTofe/+H2m5Xal79fxXnR/jbU+nbf7g6h9k5Qfa6VhefuYrY/zmn3xtjHc8
meRmrYeTXGimcvnB9ilp37YekGQ9926F3ftIWmaa6d5tK3U1t1t7Nhv2REL5gLUhp/yN3cP8nLa0
69YlaSmlDFIu63vjG98Y45NPPjnGF198cYytjIvQSpmSC0rKbDf5pZdeGmPKFUuyIMr7rrvuumxd
2bQDkK/MnTtXY2Fld5Qp9KP1OyUEPLYmuWTJgvblL395jGn3b+uFZWi/TCkQJWJnnXVWVv7EE08c
c18ob/3CF74Q4xtvvDErTxkh5SA85iOOSFNgrF69OsaUnUq5xT3to7lcqe6k3H6832RhJSmNlc+U
pDmM2fZQ3sV2yG6TecFtXnHFFTH+7ne/m5WnjOwtb3lLjNkOUZpt7dp5vVPqPHPmzBizHWLu0Crc
LkcpDq8X5lHTddSPlHKmSX7Fa9RK/EahRT7lgVIuUWXOsS45dcDll1+elacUjdc7zz8lXpS8S3n+
0lb+2GOPjTHzivvCe52F+8X7e5OVeD/LCAn33V4TzAXWfUlG2K30b0/3sxvs9kr3kVKb2nR+ecyU
BFIuyLqz9cpnpT2ddsJ7thzHcRzHcRzHcXqAv2w5juM4juM4juP0gHGVEQ5OTV3j7WG4jBjXvMe2
JZnYjllJLrdtapI67DecZCnTtj8Y483rk1OXJC09IUlxfuY3finGt//w2hjvg67G5We8LCs/e1Zy
odv2TJILtoZSV+2b3vrWGJ95YZIXStI09G7PmZ6c81rPPBrjJ1bfGuOZO5OUbcfUJH2SpOGZaV82
70xdopufSO/MrX3TNkZkunNbqYu0pT2bDXu8oesgu4bZBSzlXb1cjrIYyg/YTWxdsO64444YU/p3
wgknxPhDH/pQjO+///6sPKUgL3tZyitKB7m/F1xwQVZ+0aLkeMlubzo9UdZBNzkr5aFMp+SsyOO3
MkJK36wDZD9AaQIlhVZ+Q2kV3bJ4zj72sY/FmPlDqZyUS6Yo37rqqqtiTNkCc1TKpTncDmVW3H9K
dKRmt7tRKCOlpJG5L+W5QXkiHfF4/FYawmNrkvxMRniOSu5WUn7MlDqzDNsRuvEx76T83NENkA6n
lGHZPKbLJM8r84DnlLJDKT825sKyZctizHaIbaKVgT300EMxpiSO8aOPpvuhzVXKovpRwsxrt0ny
xO8oCacbIXOG62X7JOXnk/ch1h9zhFJBKW/vWZ73EX5u2z7mAKVgvBbocEq3Vivn5z6zPCWFJfdP
u/1+hvliJW1sP0oOeqyvpqEYpFR3TXnMvGR5ft4kaSzJtnleu3VGZF3Y9noUPgOxXuy+8Np7PnjP
luM4juM4juM4Tg/wly3HcRzHcRzHcZweMK4ywiqkLrmBQXRDGrnb9l1JcrJuOHVVL5y5MJXfenOM
D9yZ5BA7NiZXJEl6ep/UHX7coalrfdnb35UWQq/z06Z7duuuJCEJrbT/rSq9p1Y7U1fprP3zCV8P
qNCF/liSUzzzQJrM9MCtW2I8PUDuBvmAJD3xkiTbuHs95HIHJgnArgBJZiuXxVUDqUyr3b8ywibY
DcyYMgd2p1O+QEckKZdIXXLJJTGmcxcnnmVsl2O3ObvAuS90fLN/szue8h9Oivud73wnxtaZjuUp
H6GUh46F1p2MZazkqR8oTWpsoWSMEoJ3vOMdMaaU6s4774yxnayXdfaNb3wjxpyUePHixTFesWJF
sTzlfjz/lPuceeaZWXlKKHgtUM5BKRClSHQ8lPLrh/I1xsxF1p3U345ylKaw7pomA2W+UaJVqi9K
WaTcZZSSMEqLKS+zbnCUzHCCauYEzyllrlIuT7755nSvpYyRE3pzv3hctjzlZVb6OIrNlX53Qu0W
nhu2y8wrXsdsE5YuXZqtiw6EJSfS448/PsaUlkvSgw+moRnXXpuGXNB1kjJSK0NlPjHnuX1eV5S6
Whkq78O8X5YmO7ZSspKMsx8otTd2Qmx+x+uFclTWPWWI9nrrxvVvb2Jln9yfkuS8tI/MCSm/pnjM
zBe2o9aduFv30G7wni3HcRzHcRzHcZwe4C9bjuM4juM4juM4PWBcZYRqw9mkSt2Dz+qeG0wSiNs3
JQeQl8xNE3AO7p+6mvfflSaTPWRn3iX6GLq9n34ida8+MyM5ao1MQdf2YP7+ycmXQzvFg620z9Nw
XPtuy93xRrYk2cXODWvSPj+VJFtTsa5dA5BvzUuTXkrSNRuS7OOpKfNjPDQtSQ52YeLlVshlLpmM
s8+605kjlLhZBzdK3NgdTTc/SlEof7DSp7vuuivGt96aHCMpF+NExsuXL8/KUyJGWQi7tptcfSgf
2bAhTXZNWQcnNqXLnZXbcF94zHRzpOSAMhQpl5n0u5SH0gRKJ6X8PLGe3v72t8d4y5Yk+6VTm5UR
UvrKc1vKOeuExHNDWVdJhmjdllie2y/lH93BKBGScikP11uamLRJamqvs8lOSXJj5Tc8LkrkTj31
1BjTaY3r5UTpUi4JpSSR22Q7SNmhlDtT0pGMElS2nXZyc7qnUm5GiRfzjfIbOi5K+YTNbMcoY2Rd
WAe0kqNZv8Dzx7bHPvcwZ0oOgITyVMrhpfx6L7XXlFzZ809ZK9tIHgtlzjZ/KW/uRpZWkkxLec6x
fEkWZ4+3NDFuP1CSsdnrgN8xx1gvrC+2Hba++De3U5I0dlunJUlgk4yx5IbIZdgO8R5my/P+XGpv
7L2J90orUdxd+q/lchzHcRzHcRzH6QP8ZctxHMdxHMdxHKcHjKuMcEpgNyK70/PlQivt1vYdqbvz
fvSmv3ThSTHegu7J6U+aiUVHkmxi2pY1MX78mfT58H6py1v7p25DSarQdVgNp+20n4FrGaQZO+E4
KEkj21PX5X7ont0ProFbh9L2R+YnacBl63IpzsbhJOU6YM7CGD/TTl2iUwbTNoyKUCOCo1/or4lF
KS3gBJh2MkV2KbPbm93m7M5mF/L8+Umaab+79957Y0xZzDe/+c0YU3Yo5VKeJUuWxJgSPcot7LFQ
cnPllVfGmJMXcxnK0OgOJuVSIB7/5s2bY1yaJNKW6UcoO6DUgLkk5ZKdX/zFX4wxnSFvuOGGGNO1
y8pfWGeUJ/KccaJEK2mkSxLPDfOK8li6zkm5TIy5QVkZ5YKUothj4XGWnAl5/dhJkXkt9puMkPXS
NEEqv6O7GuW5bCOYh1YGyDaiJNOhxIXbk8qyZco7ee7tpLaU9rCNYk5yGeYXJ72WpKOPPjrGlFGy
7WlyICs5ufYLvCfxOK3zGa9LnidKP1mGcl66okr59cr6Y8zr0Lq18nplnlICXZIKSnm7VJJOlmRx
VsJccsxle8P8tXJsOiiuXbtW/URJAtl0jfDezftZSabK9knKc4/3kG4nEi5JRRkzPzgUQ8rvj5s2
bYpx6dqxTq6Ex8/7VsnZsal92VNHXe/ZchzHcRzHcRzH6QH+suU4juM4juM4jtMD/GXLcRzHcRzH
cRynB4zvmK0WdKbtsva9UtJ2DrSSXnjjlqTXvWMg6aAXHZrGpwxvXJWta7+tSSM+LST96SyMldjx
dKqGHdvyKhmGFXx7GHrOZ2BHuyONmapGcr1waKXvhoawrqGkfa/mJh30vz+QNKoP7kgaW0lacPiy
GG8XbZ6T/nWolbbfaudWlbuqtM129ZT6CWrFqfdtsgmmvpt6W45hoG7djlPhdyxz//33x5g24Fdf
fXVW/rrrrosxdcVcF7Facx4ndfs8Rq7r9NNPj/GyZSlXpFzfz7ESDz2UxhiWdPrSntueTjTU/TMX
7FiFk05KY0EvuuiiGFNXftttt8WY58haNHPcDcdZUbvOMTwcsyHl+ViyHy+Nx5Dy/OW1wFwqjaWy
+0K9P8tz7ADHTdixEcztZ031MckpWfhbDT/HPtAKm9bVvHZZdz/4wQ+ydbHtIKy7pjEEpToujTlb
tSq/b/I4mXtN40bGWl7Kx2kxxzi2hMdix000jefqB0o21bym7HdsS3jOeO1x7C6ng7CUcqFk6z3W
36Ow/tne2PtDqV3icrx38djt/nKc4BFHpOl/XvnKV8aY0ytwvJokXXrppTG203NMdpj7Te1maXoE
lud1yXuTHTvIsXi8Xjl+i3lgr8nSmC1+zmcQe05K7Q3zhfvI3OFzjpSP02J7U5qOwcLj9zFbjuM4
juM4juM4kxB/2XIcx3Ecx3Ecx+kB4yojHMC7XZMYIEBGqIG0ZNVKUqw1W5IMsJqeLNGPnJUsviVp
YN8kZ3kG1u/ThlOX4j6wQd/fyBuHd6VuxB27MEv3CI8glXlaOTunJDlO+8Bkk7xuOO3ninWpq3Nw
1lExPmH2MWZfUpl9WuyeTcuENk5plb9Lt6u0z8PqL1kY5W60uGZ3tJR3G9NWmzI+dpvTWtSuixa0
tE6npPG+++4bc11SLjEsyUKIlRGyC/3ggw+OMSUAlE9QumT3hdbA1mJ+rM/tPlJWaGUa/QDlDJTU
cUoASXrrW98aY0oIrr/++hjT+v3hhx+OsZUFUXZAO11OHbBy5coYWwlEydK2ZMdrZSYlmRCPi/tC
GZyVcnHfmBvr16+PMeU+lG1KeT422adPRlhf3HfKV6Tc8pxlbLsyCuV1zCMpP5fcDmPKbZqkPN1g
y5dkQqWYuf58po3otnxJ3jaZYc40yZf4HWVS3Uxb0u32CXOk6d6zu7nQtB1SsgW3U0PQ4n3p0qUx
Pu2002JMmbY9XrbLbKP6Acou+dzCe4BUluGWzjHbc1vfzD1KqCmZ5/2Mn0vlfGOOsO2ysmNe4zx3
lLYzX0pW9VK5LrhNXnf2HtqtjLMb+q/lchzHcRzHcRzH6QP8ZctxHMdxHMdxHKcHjKuMMAQ61HRZ
qNo19udhZgwf3J4cerZuz7uzD93nyBi/ZGaSYh2wKzmg7IJL4TQZGeFwWt/OEXQjoktxcDB19baH
c3new0+lrstVUJM8OJzec2cvOjPGcw4+JMY7dub7MnWI3b3sHk2VuWsY0pZ23n3fRpnB8T31ewy7
wCkPtN3G3UgruC7r4EbYhT5z5swxP+f2Zs9OclYp76qmdI37XJKYSLl8hPIJdmcfdVSSnVIOYCVO
3TjYldzBpFzOQEesfoHnj1ipHh0db7311hjTHY71RAe+Y47JZb/z5s2LMaUWJWdA5vVYf49FSSYh
5eeWMlRKM/g582fNmjXZupizpf2izOWwww7LvqNMzkqWJju8RhlbB7bSdU1XyW7drXiNz5kzJ8aU
M1MSZaU8uysDs9I9SnlK8h/KI+++++4Yb9iwoat1UWZdclOzWMlTP2Dd3kaxsmG22ZT0lpxgWWdN
EqdS/bMubdtRcpErXQuWkkyMOc/yTW6UJVdg5j9j1p2Ut3f2u8kO7088RpsTbJPZvrLueE55Tmwe
8r5BOTjrjvcN+zzAIRP8jtunVNHeg/l8xTaV+8l18Xht7pTk87wOmiTXe1O27D1bjuM4juM4juM4
PcBfthzHcRzHcRzHcXrAuGrJBgdTN163coChKskbAmRwO0PqRh2ekuRWTyrvJr5jZ3IqGdyVvnvp
LnTZD6E7fjiXyLTgL9hS6ure/lRa74ZNSU6xZXvudrP/zCSnmXJQkhXNnbMwxjuqVBebtsAlpZVL
IlvV7slvbPcoZYRt9Zccg13NjK0LUjcTONLVpqmbmN3WlNnQ/YZd7nRNkqTFixfHmNIxymcor7Ld
+exC5/a5HLv5KZdo6pq32xmF9WJdm+hGaI+zH+DEspRQWEncP/3TP8WY8h+eZzpA0rFy0aI0ubqU
O/1RlsdtUk5hZaSU2ZSkNJRQNE2ye/TRR8eYuWFdA8dar5TnKa8xlqcbJh1DpdzBsR8nph2l5A4m
5Y6L11xzTYxLkhkr3SMlZ0fKM3m92raebUfJ9Y3uo9ZJkznGPOS1s3r16hjTLZbtm5TXU2lC7CbY
Rlt5dD/AnClJ6qRcfsV7TEnG1+REyrrl9ptkx6T0HT9nm2RlbaXlmFcsw/Nqt83853LMC+YYrzcp
v5ZKks7JCp2HS3UqlScyLslzSxJOKc9D5ivPF2M7lIP3DpbnuWN52w7S4bbkmlhy6LTXAbdTmhCe
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
CCEsCSHc0IP1Tg0h3BVCmLW31z2ZCCFUIYRFE70fE0EI4UshhDf2YL0fCSH86d5erzN5CCFcEEL4
Rg/WOzuEcGcIYereXrczOZiMufOiftmqqmppVVU/6OU2Qgj/EkL4w15uox8JIawJIbx6ovdjogkh
zAwh/DCE8GgI4fEQwjUhhJfj+xBC+MMQwgMhhCdCCD8IISxtWN/Bkv6HpE91/p4SQvhqp74r++NC
Z/1/1tn+oyGEPw8hBHx/YgjhxhDCU53/T8R37wwhbAwhrOZ6QwhHhhCuDiEMjH5WVdUtkh4PIbxu
jyqsSzoP8v8YQlgbQtgaQlgRQvix8dj2ZCeEcFAI4eshhO2d+nnncxT5A0l/0U35EMKyzo9Ym0MI
H8XnQyGE60IIh41+VlXVDkn/JOnX997R7V1CCJ/v5PiTIYR7Qgg/PdH7NFGEEI4LIXy3c26rLpY/
QdIySf+Oz97ZyZntIYRvhBAOwnd/FUJ4rNMGzsPn7woh/B+z+n+Q9O7J/qLu97maEMLRIYR/DyE8
EkLY0smjxc9R7I8lxRfqEMLCEMJlnXvRXazXEMJ5nfvQxhDC2/D5gSGEm0II00c/q6rqIUmXSfrZ
vXeEex/PnZrnekYqMPlyp6oq/9fDf5L+RdIfTvR+TLZ/ktZIevVE78dE/5M0TdJi1T98BElvlLRF
0mDn+7dKelDSEZIGJP2JpJsa1verkv4v/p4i6ZckvULSRknnmOU/KOluSYdKmifpDkkfQtm1kj4q
aaqkj3T+niJpUNI6SYdI+glJt2Gd35Z0xhj79i5J3xqnet1P0u9JWtip25+QtFXSwue5vvdKumqi
82Uv1c2XJF0saf9OXjwhaWlh2UM6+Titm/KSLpH0Y51celTSnM7nvy7p18ZY/6GSNkuaOtH1Ujj+
paP7JukYSZsknVJYdrDweSVp0UQfy16oi8WSPiDpDfWjw3Mu/0lJv2Xqcqukszq580VJX+58d7qk
KzvtzP+U9Dedz18iaYWkl4yx/v8r6Vcmul6eow7WyO9zo+f3A5IOkjSk+gecuxqWP03SveazayT9
L0n7SPpJSY9LOrjz3a2SjlP9cr9F0kDn87+T9NYx1v9y3rMm4z/PnVgPjc9I/ZI7E16RE3wS10h6
teqHsq9I+mznZnC7pFPNcr+h+kH0MUn/rM7Dh8Z4CBu9uap++90laaekbZK+OdHHPBn+SfqcpLak
pzv18mudz1/fqfvHJf1A0rHdnIMx1j8g6S9VP8StlvQLnXMyiHW9Gsv/nqTP4+8zJF3d2Y+bhReU
zvle1cmT1ZLe1fl8kaTLVT94bpZ08fOol5ak13X2dVbns1+X9BUss1TSMw3r+L6kdxe+26Bnv2xd
Leln8fcHJF3biS+Q9ICkgO/XSbpQ0mxJ13Q+mybpqU78Fkn/UNj+vM45n5AHa0m3SPrJTnxOpz7+
X0kPq34RfR+WnSHpPyQ9KelHqh8Oii9bqnsT16p+wfj/mGMyP7iMbht/z5X0NUmPdHLqI/judEk3
dPbjIUn/C3X++c72Hpd0vaTZXdTBfqrbo6PN9finDcf1392Wl3Sn0svJtZ39n9+pw6HCNu6VdPZE
5MRu5s/iTp681eTQr6t+Cftc5/Nf7Sz3oKT3q+FlS9Lhkq5Q3Z78t+oXlM+PlSedz5hXLUkfk3R/
Jw++Iumg58oPFdqw3aiHReruZWuVpFfg7z+W9EX8fWQnl6ZLepukP+l8fqGkSzrx30h6Z2H975J0
2UTnRcPx+32uXDcHdfZ1RuH735H0afx9tKQdkqbjsyuVfhhchc83SZqluu35TmH9g5KekrRgovPE
c2e36uVZz0j9kjsvahmh4fWSvizpQNUPWX9jvn+XpNeovkEcLem3n2uFVVX9g6QvSPrzqqr2r6pq
XCRUk52qqn5K9UP76zr18uchhKNV/2L+S5IOVv0L+TdDCFNQtNtz8DOqf10/UdLJqn8J6YqOfOXb
kv5Q9Q3hVyR9LYRwcAhhP0mfkPRjVVVNl/QySSs7Rf9A0n9JeqnqX+v/Guv8VgjhY8+x3VskPaM6
9z5dVdXDna++LGlRR4YxJOk9kr7TsKrjVfdUdctS1Y3lKDd3Phv97paq08J0uKXz+SOSZoQQDpV0
vqTbQwj7qz4nvzHWhqqqekD1jw/PJR/Z64QQZqvOmdvx8RzVv5zPU/2S+ckQwks7331S9fk4RPUD
8/sb1r1E0t+qzs9DsM5u9qsl6Zuq632epPMk/VII4TWdRf6PpP9TVdUBqvP+K53P39PZzmGqXww/
pPrGrBDCx0II3yps8mhJI1VV3YPPeM4tNp+eq/xtki7o5MVC1S8Cn1D9sLCrsI07Vf+qOCkJIfxt
COEpSXepfom6BF/PUd1OLJD0syGEC1W3GedLOkr1j3lNfFH1i+gM1Q80P7Ubu/YR1W3b2apf2B9T
nbdSIT+a2rAQwvyOTGf+buzDmHS2c7jy3Mnamqqq7lfnxV31dfnKEMI+qq+B20MIp0paXFXVFwub
mdR54/e5Rs6StKmqqkcL39t2Z6nqh+Kt+IztzsMdCfMy1S8pj0n6K9XXyLOoqmpY0n2apPnjuTPm
dkvPSJZJmTv+spW4qqqqS6qqGlH9q4KtyL+pqmp9VVVbJP2RpHeM+x6+sHmbpG9XVfW9zkPZX6ju
8n0Zlun2HLxV9QPqhqqqHhO0u13wbtW/ql5SVVW7qqrvqe5Z+PHO921Jx4UQ9qmqamNVVaMP77tU
P3DNrarqmaqqoplCVVU/UVVV4z5UVXWCpAMkvVMSjRg2qv4V5m7VD9MXqZb1lThQ9S9K3bK/6l+a
RnlC0v4hhDDGd6PfT6+qqi3p5yR9VXVj+zOSPq66AT2+o4/+bgjhOFN+a2cfx43OS+oXJH2mqqq7
8NUuSR+vqmpXVVWXqP4FcXGox5r9pKTfqapqe1VVt0n6TMMm3qK61/qqqqp2qv5lrWpYnpymWs7w
8aqqdlZVtUq1POrt2MdFIYSZVVVtq6rqWnw+Q3WPyUhVVTdWVfWkJFVV9adVVf1EYXvFc1pY3ubT
c5X/FdV58R+q8/TlnfKrOmM2Lg8hXGTKj3tO7A5VVX1Y9fG9UtK/qf6VdJS2pN+tqmpHVVVPq257
/rmqqtuqqtqu+gVqTDovNaepzrOdnTbjP3Zj1z6oWqa3oarHv/2epLeEEAbVkB8qtGFVVa2rqurA
qqrW7cY+lBg9n13lTuca+5rq3tD5kv5M9Q8NHwm1GcYVIYQvhBCYJ1tVv1D2Ey/q+5wkdX6I+aSk
X25YbHfbnQ+pzpd/UP2Dxc9JulTStM596LIQwtmm/KRud8bgRZ07Dc9IlkmZO/6yldiE+CnVFT2I
z9YjXqv6l0Rn7zFXdb1KkjoP8+uV9xB0ew7mmmXXF5YbiwWSLur8wvt4COFx1eNSDuk8PL1N9cW5
MYTw7RDCMZ1yv6ZaT/yjUBsEFHtCSnQaoC9J+ljnVxZJ+l3VD2SHqZYG/b6k74cQ9i2s5jGVH5zH
YpvqBmyUAyRt6/Rm2e9Gv9/a2d9Lq6o6o6qqs1U3sKeqlsx9TrWU4A8kfdqUn65aejAudHqOPqf6
F/RfMF8/2vmVapSnVDfMB6uWCth8K5HlW1VVT6mWb3XDAklzTb79pmqZplT3uB0t6a4QwvUhhNGX
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
XptPsDawb9p+ayDJbNptTGyLYxkcyrvTKXsIbUot0nvu0NR0LCO7krRgcDCXqYxUmJRtenJZ2b49
ycKGplCykcsQ+3laY9Zj0wSahDINyg9KsiAr66C0hjIods1TImNlMSXJCz+nRMdOxkhHMnbNl9y6
2LVuZR2cVDeT1sL1inXURD+6EZawEivKCM8444wY33NPant4nljPlCxI0uGHp8nKKcUpybqaJFLM
Lcbz5s2LMWUWUi6f4XXCXGIuc2JT677IbTL/OHFyk+sayzdds5MRni+2F00SZF4jvPZIyeGxafs8
Lzy/9nxRNlpyLWySU1OmRJlNqe3tduLhUpvcrWy5Sbo5WaEUibGdQJXngPXJNprnknI5K+Vie7Ns
2bIYn3nmmTEuOYTa7ZcmQqZ0ke6FUp7PpYmwb7rpphjTSdVOaky5IbdPSSXLdDMBe7/QrXSNbQlj
1hHziJPZW/dHOtxeckkaFsO6P+WUU8aM7XLMI+YE94VSdvt3yQmVrprf+c53YnzjjTdm62J5Ou/y
vkXHQttWsox9PttdvGfLcRzHcRzHcRynB/jLluM4juM4juM4Tg8YVxnhE9tSl+ajDydXpiOPXJgt
NwBFxc4RdBVvT93Ohxz45hi3qjRB2chwLocYhJRuCF3lO0Yg/Wul7vAFh702K//17/zvGL/i7MUx
btM1sJUkMk88kUuJbl6ZnF02P5K6K2+68fZU5pE0KfJQK8kMhofTsUvScEgudhvW/yDtS6CEoPz+
3IdGTpGSjMlK90puT6Xy7GbmJLBSLtFitzsnfKX0g933dpvPx4GN3e7sQmcXPKWD/JwSRPt3aVJa
Sk/s5JH9Jv2y8JhLsZRLe84666wY33DDDWPGLG/lK5RjzJ8/P8aUMDS5s/G7kqMbP7cTmZZkoZSu
UjpIGaStF26TecJrjBIheyzMn35zumS7wGu/W5ezkgsYsfVVai/YdnH7VnpFyQvLlBxaKY+0fzMX
WL7UJtjcYY6W6oxtl5UK9rsbYUlWaaWbvJZKkxKXJlq3Dn4l+RXlfmyTKG+U8jrnOed+NZ0z7htl
tFdddVWMV6xYEWO69VpnRd57uS+8p/EatblM+s0Jlfvb5PbK6515VJIdU+Jur+O77rorxiV5Jycy
Xr58eVZ+8eL0nMx7HXOn6Zpm7jJ3rr322hhfcUV6ZmZO2faF+8Jj5r2K9zPrykkHQ5/U2HEcx3Ec
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
oWyzlMTyHKOMkFIRHidKdrK69Fnkb3WG2qhnsj7GmSSub18ZfdK9rI1lxPLZOzaz0e6TNPLvTBLW
1yaGysa3KnxG+RzHc6EFNcvQYp3PG9/D8bpmy5uwPPvKKL/i/3hvuN++ezFEOjt0v0Os27lf1j2W
mbX2c+2113bxyZMnuzjeb1q8ZxbttIcn8dljO8zuEb9BonU7bdXZRvndxHsUZYTcjtI9timWZ394
/vz5ksHtGPOZ4O+ltNJNSmg3gjNbIiIiIiIiI+BgS0REREREZAQmG3HWEhERERERkX6c2RIRERER
ERkBB1siIiIiIiIj4GBLRERERERkBBxsiYiIiIiIjICDLRERERERkRFwsCUiIiIiIjICDrZERERE
RERGwMGWiIiIiIjICDjYEhERERERGQEHWyIiIiIiIiPgYEtERERERGQEHGyJiIiIiIiMgIMtERER
ERGREXCwJSIiIiIiMgIOtkREREREREbAwZaIiIiIiMgIONgSEREREREZAQdbIiIiIiIiI+BgS0RE
REREZAQcbImIiIiIiIyAgy0REREREZERcLAlIiIiIiIyAg62RERERERERuA/L+P/hjUWZp8AAAAA
SUVORK5CYII=
)

In \[24\]:

fig, axs = plt.subplots(6,2, figsize=(9, 19))
axs = axs.ravel()

for i in range(len(my\_softmax\_logits)):
    axs\[2*i\].axis('off')
    axs\[2*i\].imshow(images\[i\])
    axs\[2*i+1\].bar(np.arange(n_classes), my\_softmax\_logits\[i\]) 
    axs\[2*i+1\].set_ylabel('Softmax probability')

![](data:image/png;base64,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
)

### Project Writeup[¶](#Project-Writeup)

Once you have completed the code implementation, document your results in a project writeup using this [template](https://github.com/udacity/CarND-Traffic-Sign-Classifier-Project/blob/master/writeup_template.md) as a guide. The writeup can be in a markdown or pdf file.

> **Note**: Once you have completed all of the code implementations and successfully answered each question above, you may finalize your work by exporting the iPython Notebook as an HTML document. You can do this by using the menu above and navigating to \\n", "**File -> Download as -> HTML (.html)**. Include the finished document along with this notebook as your submission.

* * *

Step 4 (Optional): Visualize the Neural Network's State with Test Images[¶](#Step-4-(Optional):-Visualize-the-Neural-Network's-State-with-Test-Images)
------------------------------------------------------------------------------------------------------------------------------------------------------

This Section is not required to complete but acts as an additional excersise for understaning the output of a neural network's weights. While neural networks can be a great learning device they are often referred to as a black box. We can understand what the weights of a neural network look like better by plotting their feature maps. After successfully training your neural network you can see what it's feature maps look like by plotting the output of the network's weight layers in response to a test stimuli image. From these plotted feature maps, it's possible to see what characteristics of an image the network finds interesting. For a sign, maybe the inner network feature maps react with high activation to the sign's boundary outline or to the contrast in the sign's painted symbol.

Provided for you below is the function code that allows you to get the visualization output of any tensorflow weight layer you want. The inputs to the function should be a stimuli image, one used during training or a new one you provided, and then the tensorflow variable name that represents the layer's state during the training process, for instance if you wanted to see what the [LeNet lab's](https://classroom.udacity.com/nanodegrees/nd013/parts/fbf77062-5703-404e-b60c-95b78b2f3f9e/modules/6df7ae49-c61c-4bb2-a23e-6527e69209ec/lessons/601ae704-1035-4287-8b11-e2c2716217ad/concepts/d4aca031-508f-4e0b-b493-e7b706120f81) feature maps looked like for it's second convolutional layer you could enter conv2 as the tf_activation variable.

For an example of what feature map outputs look like, check out NVIDIA's results in their paper [End-to-End Deep Learning for Self-Driving Cars](https://devblogs.nvidia.com/parallelforall/deep-learning-self-driving-cars/) in the section Visualization of internal CNN State. NVIDIA was able to show that their network's inner weights had high activations to road boundary lines by comparing feature maps from an image with a clear path to one without. Try experimenting with a similar test to show that your trained network's weights are looking for interesting features, whether it's looking at differences in feature maps from images with or without a sign, or even what feature maps look like in a trained network vs a completely untrained one on the same sign image.

![Combined Image](visualize_cnn.png)

Your output should look something like this (above)

In \[ \]:

\### Visualize your network's feature maps here.
\### Feel free to use as many code cells as needed.

\# image_input: the test image being fed into the network to produce the feature maps
\# tf_activation: should be a tf variable name used during your training procedure that represents the calculated state of a specific weight layer
\# activation_min/max: can be used to view the activation contrast in more detail, by default matplot sets min and max to the actual min and max values of the output
\# plt_num: used to plot out multiple different weight feature map sets on the same block, just extend the plt number for each new feature map entry

def outputFeatureMap(image_input, tf_activation, activation_min=-1, activation_max=-1 ,plt_num=1):
    \# Here make sure to preprocess your image_input in a way your network expects
    \# with size, normalization, ect if needed
    \# image_input =
    \# Note: x should be the same name as your network's tensorflow data placeholder variable
    \# If you get an error tf_activation is not defined it may be having trouble accessing the variable from inside a function
    activation = tf_activation.eval(session=sess,feed_dict={x : image_input})
    featuremaps = activation.shape\[3\]
    plt.figure(plt_num, figsize=(15,15))
    for featuremap in range(featuremaps):
        plt.subplot(6,8, featuremap+1) \# sets the number of feature maps to show on each row and column
        plt.title('FeatureMap ' + str(featuremap)) \# displays the feature map number
        if activation_min != -1 & activation_max != -1:
            plt.imshow(activation\[0,:,:, featuremap\], interpolation="nearest", vmin =activation_min, vmax=activation_max, cmap="gray")
        elif activation_max != -1:
            plt.imshow(activation\[0,:,:, featuremap\], interpolation="nearest", vmax=activation_max, cmap="gray")
        elif activation_min !=-1:
            plt.imshow(activation\[0,:,:, featuremap\], interpolation="nearest", vmin=activation_min, cmap="gray")
        else:
            plt.imshow(activation\[0,:,:, featuremap\], interpolation="nearest", cmap="gray")
