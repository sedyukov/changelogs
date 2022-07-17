### Changelog

All notable changes to this project will be documented in this file. Dates are displayed in UTC.


### [v1.4.0](https://bitbucket.org/decimalteam/go-node/compare/v1.4.0..v1.3.0) - 2022-07-14

#### Fixes

* Consensus failure problem [`#26239`](https://bitbucket.org/decimalteam/go-node/pull-requests/87)

### [v1.3.0](https://bitbucket.org/decimalteam/go-node/compare/v1.3.0..v1.2.15) - 2022-06-29

#### Features

* Coin burn [`#32285`](https://bitbucket.org/decimalteam/go-node/pull-requests/84)


### [v1.2.15](https://bitbucket.org/decimalteam/go-node/compare/v1.2.15..v1.2.14) - 2022-06-09

#### Fixes

* Jailing absent validators without slashing [`#31324`](https://bitbucket.org/decimalteam/go-node/pull-requests/83)


### [v1.2.14](https://bitbucket.org/decimalteam/go-node/compare/v1.2.14..v1.2.13) - 2022-06-02

#### Fixes

* Incorrect removing unbounding delegations records from the state in rare cases [`#29829`](https://bitbucket.org/decimalteam/go-node/commits/51a74d5bcd9855da09f097ba241032c8b90fe628)
* Compensations [`#28883`](https://bitbucket.org/decimalteam/go-node/pull-requests/82)
    * Supported compensation mechanism and specific function compensating wrong slashes happened at 9288729 block
    * Removed commas from amounts in NFT compensations
    * Removed panics from compensation code to make it safer
    * Slashes for double signing is turned off now while in grace period

### [v1.2.13](https://bitbucket.org/decimalteam/go-node/compare/v1.2.13..v1.2.12) - 2022-04-29

#### Fixes

- Issue for case when all slots of validator are used. [`#27660`](https://bitbucket.org/decimalteam/go-node/pull-requests/81)


### [v1.2.12](https://bitbucket.org/decimalteam/go-node/compare/v1.2.12..v1.2.10) - 2022-03-30


#### Features

- Extended log info for failed transactions with code 4 [`#22265`](https://bitbucket.org/decimalteam/go-node/pull-requests/74)

#### Fixes

- Counting MissedBlockCounter [`#23003`](https://bitbucket.org/decimalteam/go-node/pull-requests/75)
- Important optimizations in modules validator, gov and swap. [`#22943`](https://bitbucket.org/decimalteam/go-node/pull-requests/73)
- Download upgrades and check hashes for new files [`#22158`](https://bitbucket.org/decimalteam/go-node/pull-requests/71)
- Sync (forgotten) error wrapping from staging to master [`#14831`](https://bitbucket.org/decimalteam/go-node/pull-requests/55)
- Add missed aliases [`#8812`](https://bitbucket.org/decimalteam/go-node/pull-requests/58)
- Prevent incorrect detection of grace period [`#21666`](https://bitbucket.org/decimalteam/go-node/pull-requests/70)
- Removed pruning option of app.conf overwriting and extended grace period to 182 days [`#23473`](https://bitbucket.org/decimalteam/go-node/pull-requests/52)

### [v1.2.10](https://bitbucket.org/decimalteam/go-node/compare/v1.2.10..v1.2.9) - 2022-02-16
#### Features
* Updated one hour of grace period duration [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/91cac290ad38f8f0ab94999493872133d281b036)

### [v1.2.9](https://bitbucket.org/decimalteam/go-node/compare/v1.2.9..v1.2.8) - 2022-02-16
#### Features
* Update grace period hour length [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/3d93560970e0867eeb7578138a7c20b51ac49c60)
* Updating deploy Centos 8 [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/4749b52edeae1f6b4af13b65b9a25b9c19eab02c)

### [v1.2.8](https://bitbucket.org/decimalteam/go-node/compare/v1.2.8..v1.2.7) - 2022-02-04
#### Features
* Extended grace period [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/b0826f6a32ce6006c49f6e713818dfdf0f297313)

### [v1.2.7](https://bitbucket.org/decimalteam/go-node/compare/v1.2.7..v1.2.6) - 2022-01-26
#### Features
* Added build on ubuntu 22.04 [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/5afd8c8b26b86126217c908dd9a3912e6e35cb8f)
#### Fixes
* Missing blocks count [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/81a363b605038abb43ed58803fef83b1a4304f75)

### [v1.2.6](https://bitbucket.org/decimalteam/go-node/compare/v1.2.6..v1.2.5) - 2022-01-26
#### Features
* Update block [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/121a8b8c16068f27ffc50dba1225c7b98e6d222b)
* Update slash & sync_delegate [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/dfbaa4b904c4f34abda0d3256d3eafc70b0dea58)
* Up cosmos-sdk 0.39.3 [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/66491a394d5ec57d42bd6d712b9fc92110150de9)
* Update nft reserver [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/5e1db4371c2deb062ca5862bbd43e8a650bde206)
* Append sort(unbond_nft), change(missed_blocks), sync(delegated_coin) [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/cb72159a9b79683c77bc0edac059814acf252219)
#### Fixes
* Change with [decd 'non-start'] [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/fb2c82a305f3cb899641b7215efce99967a879ea)
* Delete sort in unbond_nft [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/afea4f7ab3d62969744c6f86885625e79739b75e)

### [v1.2.5](https://bitbucket.org/decimalteam/go-node/compare/v1.2.5..v1.2.4) - 2021-12-14
#### Features
* Exec.path [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/52ab4e5ae768a28b3254a1af9bd07ba12c364f2b)
#### Fixes
* Unbound and update delegated coin [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/eea305cb3031f9b56dc9a8d0315029b43397f2f2)

### [v1.2.4](https://bitbucket.org/decimalteam/go-node/compare/v1.2.4..v1.2.3) - 2021-12-14
#### Features
* Improved readme [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/deea294a134d3c65c634a9b2a5e340f45c063b37)

### [v1.2.3](https://bitbucket.org/decimalteam/go-node/compare/v1.2.3..v1.2.2) - 2021-12-14
#### Features
* Update autoupgrade & delegation [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/e66b61de5f9035da23999d9c168e2bde789e0219)
* Update12Block(back to 6503421) [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/20a07396968df6ad332b91a2a2b75771e817fe59)
* Add events [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/7eb5e0bba867befbf35404b59a94dde0230cdf9e)
* Complete unbounding delegations [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/fe6faeac0432d3fc43c4e503591ba5a325a62fa1)
* Sync pools and stakes of validators [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/80c4ad66bc6511124263dd44a162571382c91aba)
* UpdateCoin transactions, identity for coin, remove validatorCache [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/71e5110be36754079ce4c6d660242757a2e4e5ca)
#### Fixes
* Resolve addBlocks error [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/74b0f1f2a751dd62a1c017f6c6b7896062ae351a)
* Validator errors [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/d2dd902bffd35c033738c8a198c02d3bc2aa1a22)
* Update deploy - remove ubuntu 19.04 [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/366dea9311df77713904c2d5409b4559d7b7ac99)
* Remove delegationNFT [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/9b1248f0fc39110f5f79f4fc72c606f9d07ad614)
* Uploading bug resolved [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/eb1f8654e6048e7dbb22976120e8b765e98f76aa)

### [v1.2.2](https://bitbucket.org/decimalteam/go-node/compare/v1.2.2..v1.2.1) - 2021-12-14
#### Features
* Set if.block [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/409c90444fb732cb5b588627e52711ad076929f9)
* Events renamed 'SoftwareUpgrade' -> 'software_upgrade' [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/ba79aa2b98e632e3fd6fd4b179e1f9d6ea0d4c4b)
* Check coin exists , fix delegate , check recv in send coin [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/166700e223a8efec8611e04d5475272a73541972)

### [v1.2.1](https://bitbucket.org/decimalteam/go-node/compare/v1.2.1..1.1.14) - 2021-10-28
#### Features
* Set update_block & grace_period [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/822db1538bcde364941e0e06635e6758c3ea6e75)
* Set static grace period [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/c4adf281db89d4210963e28b4779ca1e1d3fa878)
* Set grace period 15 minutes [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/9e9bf31cb6d81b241361c6eea4fc50210cc4c8a5)
* Update check exec [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/a9a73536850748bf5b2da9569cc1e1a07bc85543)
* Add the update const and without slash period [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/31eb5332c1d5f2f6db14acf5a18b8f8b7345fe7f)
* License added [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/350827b99a5edf81a452b0c22ab6edb5e9c76b54)
#### Fixes
* Min.reserve change [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/d7df694687cf391fe0c55023b9e6105995f51961)
* Nft min reserve [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/160b90aad43678058bbdd8b4fd5ab7b3a952cfb5)

### [1.1.14](https://bitbucket.org/decimalteam/go-node/compare/1.1.14..v1.0.4) - 2021-07-27
#### Features
- Information about errors [`#5835`](https://bitbucket.org/decimalteam/go-node/pull-requests/4)

### [v1.0.4](https://bitbucket.org/decimalteam/go-node/compare/v1.0.4..v1.0.3) - 2020-08-06
#### Fixes
- Pay rewards after edit-candidate with new reward address [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/2bd760bbf2066359df817efb088044aa5a44f867)

### [v1.0.3](https://bitbucket.org/decimalteam/go-node/compare/v1.0.3..v1.0.2) - 2020-08-05
#### Fixes
- Change validators slots count calculation and improved gas consuming [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/da6d83eabdec184900013d00f38ffdcd86a70b9a)
- Change gas wanted, equal to gasUsed [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/6d5cbd97632e544ab9446fd3c16d4fa8a7b6590f)

### [v1.0.2](https://bitbucket.org/decimalteam/go-node/compare/v1.0.2..v1.0.0) - 2020-08-03
#### Features
* Updated block for update behavior [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/29b8ff8d84a63a6a91354fc6d1a88f4f2aed5aa6)
#### Fixes
* Resolved problem with redeem checks and creating coins [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/b788968793823d04aef31e0c746285329783f6ce)
* Fixed problem with redeem checks and creating coins [`COMMIT`](https://bitbucket.org/decimalteam/go-node/commits/4e35c61c2e00deacf04693f23519633cdadfce93)

