## About Me (⭐ Open to offers)

I build reliable, production-grade software for companies that can't afford downtime, over 10 years shipping enterprise and freelance projects for clients in **🇺🇸 USA, 🇨🇦 Canada, 🇬🇧 UK, 🇫🇷 France, 🇦🇺 Australia**, and beyond.

**Have a project or an offer?** Email me at `lazerg2@gmail.com`, or message [@lazizbek_ergashev](https://t.me/lazizbek_ergashev) on Telegram for an instant reply.

---

## Latest contributions

🚀 I spend my free time hunting bugs and shipping fixes to the open source tools I rely on daily, my small way of paying the community back.

**`php/php-src`**
- [#25239](https://github.com/php/php-src/pull/25239): Fix GH-25238: ReflectionProperty::isInitialized() skips lazy init once cached
- [#25087](https://github.com/php/php-src/pull/25087): Fix GH-25086: IoPoll kqueue backend leaks memory on every modifyEvents()
- [#24614](https://github.com/php/php-src/pull/24614): Fix GH-24609: mysqlnd OK packets without info rejected on x32 builds
- [#25012](https://github.com/php/php-src/pull/25012): Fix GH-25007: PFA named args in constant expression write out of bounds
- [#25027](https://github.com/php/php-src/pull/25027): Fix GH-25023: ZEND_CONTAINER_OF() fails to compile with -std=c11

**`laravel/framework`**
- [#62299](https://github.com/laravel/framework/pull/62299): [13.x] Fix JSON:API resource collections wrapping plain objects
- [#61859](https://github.com/laravel/framework/pull/61859): [13.x] Fix parallel testing with PHPUnit 13.4
- [#61769](https://github.com/laravel/framework/pull/61769): [13.x] Fix `Builder::with()` when a null callback is passed explicitly
- [#61708](https://github.com/laravel/framework/pull/61708): [13.x] Don't swallow deadlocks in `DatabaseLock` inside a transaction
- [#61597](https://github.com/laravel/framework/pull/61597): [13.x] Fix Eloquent Collection duplicates() with a key or callback
- [#61405](https://github.com/laravel/framework/pull/61405): [13.x] Restore the container instance after route:cache boots a fresh application
- [#61397](https://github.com/laravel/framework/pull/61397): [12.x] Fix TypeError in userFromRecaller() when the recaller matches no user
- [#61201](https://github.com/laravel/framework/pull/61201): [13.x] Keep the assertion failure message when session errors are JSON serialized
- [#61139](https://github.com/laravel/framework/pull/61139): [13.x] Avoid cross-slot reads when checking paused queues
- [#60921](https://github.com/laravel/framework/pull/60921): [13.x] Fix appended accessors receiving null in toArray()
- [#60815](https://github.com/laravel/framework/pull/60815): [13.x] Fix resolveClassAttribute() cache key omitting the property
- [#60574](https://github.com/laravel/framework/pull/60574): Clear transaction manager state on disconnect

**`symfony/*`**
- [symfony/ai#2868](https://github.com/symfony/ai/pull/2868): [AI Bundle] Keep the tool call listeners working without the security or validator service
- [symfony/ai#2816](https://github.com/symfony/ai/pull/2816): [Agent] Fix Redis message store staying in WATCH and overwriting keys it cannot read
- [#68142](https://github.com/symfony/symfony/pull/68142): [DoctrineBridge] Fix UniqueEntity default error path when fields is a mapping
- [#67988](https://github.com/symfony/symfony/pull/67988): [Messenger] Fix parallel workers crashing on errors that cannot be serialized
- [#68023](https://github.com/symfony/symfony/pull/68023): [AssetMapper] Resolve the env vars of `asset_mapper.server` when the container is compiled
- [#67966](https://github.com/symfony/symfony/pull/67966): [HttpKernel] Fix the bundle cache dumped by `parent::dumpContainer()` in a `MicroKernelTrait` kernel
- [#67974](https://github.com/symfony/symfony/pull/67974): [TypeInfo] Fix infinite recursion in `Type::fromValue()` with cyclic values
- [#67925](https://github.com/symfony/symfony/pull/67925): [HttpClient] Keep the response decorated by TraceableResponse usable until it is freed
- [#67845](https://github.com/symfony/symfony/pull/67845): [Security] Fix the login throttling message announcing one minute too many
- [#67864](https://github.com/symfony/symfony/pull/67864): [Cache] Fix fetching long keys with MemcachedAdapter::getItems()

**`nodejs/node`**
- [#66769](https://github.com/nodejs/node/pull/66769): sqlite: retry busy or locked backup steps
- [#66895](https://github.com/nodejs/node/pull/66895): src: fix build with `--shared-brotli`
- [#66671](https://github.com/nodejs/node/pull/66671): crypto: do not leak scrypt param check errors
- [#66694](https://github.com/nodejs/node/pull/66694): crypto: fix X509 curve name crash for non-NIST curves
- [#66565](https://github.com/nodejs/node/pull/66565): module: fix require of imports with package map

**`vuejs/core`**
- [#15634](https://github.com/vuejs/core/pull/15634): fix(runtime-core): detect new prop keys when comparing full props
- [#15711](https://github.com/vuejs/core/pull/15711): fix(KeepAlive): unmount pruned current component when its vnode was cloned on mount
- [#15604](https://github.com/vuejs/core/pull/15604): fix(compiler-sfc): error when defineModel prop options reference a destructured prop
- [#15753](https://github.com/vuejs/core/pull/15753): fix(runtime-vapor): run app mounted hooks after hydration ends
- [#15595](https://github.com/vuejs/core/pull/15595): fix(vapor): hydrate custom element children

**`react/react`**
- [#38025](https://github.com/react/react/pull/38025): [rust-compiler] Fix non-ASCII panic in is_ref_like_name
- [#38007](https://github.com/react/react/pull/38007): [RN] Call dispatchNativeEvent when the event target is null
- [#37730](https://github.com/react/react/pull/37730): [Flight] Fix reviving errors without stack frames in debug info
- [#37389](https://github.com/react/react/pull/37389): [DOM] Copy `source` onto the synthetic toggle event

**`react/react-native`**
- [#59955](https://github.com/react/react-native/pull/59955): Retry SwiftPM artifact version lookups on transient failures
- [#59954](https://github.com/react/react-native/pull/59954): Expose `rrc_scrollview` via prefab
- [#59953](https://github.com/react/react-native/pull/59953): Dedupe @typescript-eslint/utils for eslint-plugin-jest in yarn.lock
- [#59760](https://github.com/react/react-native/pull/59760): Look up props read out of order by name in RawPropsParser
- [#59709](https://github.com/react/react-native/pull/59709): Add bun lockfiles to default lockFiles in autolinkLibrariesFromCommand

---

![Profile views](https://komarev.com/ghpvc/?username=lazerg&label=Profile%20views&color=0e75b6&style=flat)
