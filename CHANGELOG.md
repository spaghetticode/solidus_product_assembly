# Change Log

## [Unreleased](https://github.com/solidusio-contrib/solidus_product_assembly/tree/HEAD)

[Full Changelog](https://github.com/solidusio-contrib/solidus_product_assembly/compare/v1.0.0...HEAD)

**Closed issues:**

- Wrong return item amounts when returning orders with line items with quantity \> 1 [\#46](https://github.com/solidusio-contrib/solidus_product_assembly/issues/46)
- Deface is required [\#37](https://github.com/solidusio-contrib/solidus_product_assembly/issues/37)
- Javascript not registering Events [\#23](https://github.com/solidusio-contrib/solidus_product_assembly/issues/23)
- Cannot select parts [\#18](https://github.com/solidusio-contrib/solidus_product_assembly/issues/18)

**Merged pull requests:**

- Show split/delete actions for all items \(admin/orders/shipment\) [\#49](https://github.com/solidusio-contrib/solidus_product_assembly/pull/49) ([MinasMazar](https://github.com/MinasMazar))
- Show correct RMA amounts when assembly has more than one piece for var… [\#48](https://github.com/solidusio-contrib/solidus_product_assembly/pull/48) ([spaghetticode](https://github.com/spaghetticode))
- Fix build on Travis [\#47](https://github.com/solidusio-contrib/solidus_product_assembly/pull/47) ([spaghetticode](https://github.com/spaghetticode))
- Fix return item amounts with multiple items [\#45](https://github.com/solidusio-contrib/solidus_product_assembly/pull/45) ([spaghetticode](https://github.com/spaghetticode))
- add deface as a development dependency in gemspec [\#44](https://github.com/solidusio-contrib/solidus_product_assembly/pull/44) ([kevinjbayer](https://github.com/kevinjbayer))
- Round up default refund amount for assembly parts [\#43](https://github.com/solidusio-contrib/solidus_product_assembly/pull/43) ([spaghetticode](https://github.com/spaghetticode))
- Remove assembly part prices from carton manifest [\#42](https://github.com/solidusio-contrib/solidus_product_assembly/pull/42) ([spaghetticode](https://github.com/spaghetticode))
- Split refund amount proportionally on each assembly part [\#41](https://github.com/solidusio-contrib/solidus_product_assembly/pull/41) ([spaghetticode](https://github.com/spaghetticode))
- Fix stock finalization with non-backorderable stock and Solidus \>= 2.8 [\#40](https://github.com/solidusio-contrib/solidus_product_assembly/pull/40) ([spaghetticode](https://github.com/spaghetticode))
- Replace `Spree.t` with `I18n.t` [\#38](https://github.com/solidusio-contrib/solidus_product_assembly/pull/38) ([spaghetticode](https://github.com/spaghetticode))
- Lock SQLite3 to version 1.3 [\#36](https://github.com/solidusio-contrib/solidus_product_assembly/pull/36) ([aitbw](https://github.com/aitbw))
- Add Solidus v2.8 to Travis config [\#35](https://github.com/solidusio-contrib/solidus_product_assembly/pull/35) ([aitbw](https://github.com/aitbw))
- Remove stale edit button [\#34](https://github.com/solidusio-contrib/solidus_product_assembly/pull/34) ([spaghetticode](https://github.com/spaghetticode))
- Use Selenium with Chrome headless instead of Poltergeist [\#33](https://github.com/solidusio-contrib/solidus_product_assembly/pull/33) ([spaghetticode](https://github.com/spaghetticode))
- Fix `stock\_item` partial for splitting items [\#32](https://github.com/solidusio-contrib/solidus_product_assembly/pull/32) ([spaghetticode](https://github.com/spaghetticode))
- Fix admin edit for shipping costs and tracking [\#31](https://github.com/solidusio-contrib/solidus_product_assembly/pull/31) ([spaghetticode](https://github.com/spaghetticode))
-  AvailabilityValidator delegates to Solidus implementation when product is not an assembly [\#30](https://github.com/solidusio-contrib/solidus_product_assembly/pull/30) ([spaghetticode](https://github.com/spaghetticode))
- Test suite maintenance [\#29](https://github.com/solidusio-contrib/solidus_product_assembly/pull/29) ([aitbw](https://github.com/aitbw))
- Remove 2.2 from CI \(EOL\) [\#28](https://github.com/solidusio-contrib/solidus_product_assembly/pull/28) ([jacobherrington](https://github.com/jacobherrington))
- Remove versions past EOL from .travis.yml [\#27](https://github.com/solidusio-contrib/solidus_product_assembly/pull/27) ([jacobherrington](https://github.com/jacobherrington))
-  Add Solidus 2.7 to .travis.yml [\#26](https://github.com/solidusio-contrib/solidus_product_assembly/pull/26) ([jacobherrington](https://github.com/jacobherrington))
- Update for Solidus 2.5 [\#21](https://github.com/solidusio-contrib/solidus_product_assembly/pull/21) ([jhawthorn](https://github.com/jhawthorn))
- Fix warnings [\#20](https://github.com/solidusio-contrib/solidus_product_assembly/pull/20) ([jhawthorn](https://github.com/jhawthorn))
- 2.4 fixes [\#19](https://github.com/solidusio-contrib/solidus_product_assembly/pull/19) ([jhawthorn](https://github.com/jhawthorn))
- Avoid stubbing in spec [\#17](https://github.com/solidusio-contrib/solidus_product_assembly/pull/17) ([jhawthorn](https://github.com/jhawthorn))
- Remove old Spree information from README [\#16](https://github.com/solidusio-contrib/solidus_product_assembly/pull/16) ([brchristian](https://github.com/brchristian))
- Removing small\_image Method Call. Replacing It To Avoid Error. [\#15](https://github.com/solidusio-contrib/solidus_product_assembly/pull/15) ([hugohernani](https://github.com/hugohernani))
- Fix deprecations and removals [\#14](https://github.com/solidusio-contrib/solidus_product_assembly/pull/14) ([jhawthorn](https://github.com/jhawthorn))
- Remove add\_routes fo routes.draw [\#13](https://github.com/solidusio-contrib/solidus_product_assembly/pull/13) ([denissellu](https://github.com/denissellu))
- Fix migration to allow rollback [\#12](https://github.com/solidusio-contrib/solidus_product_assembly/pull/12) ([tudorpavel](https://github.com/tudorpavel))
- Parts informations in API [\#11](https://github.com/solidusio-contrib/solidus_product_assembly/pull/11) ([DanielePalombo](https://github.com/DanielePalombo))

## [v1.0.0](https://github.com/solidusio-contrib/solidus_product_assembly/tree/v1.0.0) (2016-09-06)
**Closed issues:**

- Inventory Validation fail upon checkout, for the assembly product [\#3](https://github.com/solidusio-contrib/solidus_product_assembly/issues/3)

**Merged pull requests:**

- Add support for Solidus 2.0 and Rails 5 [\#10](https://github.com/solidusio-contrib/solidus_product_assembly/pull/10) ([jhawthorn](https://github.com/jhawthorn))
- Fix installation instructions in README [\#9](https://github.com/solidusio-contrib/solidus_product_assembly/pull/9) ([alexblackie](https://github.com/alexblackie))
- Add missing translation for actions.delete [\#8](https://github.com/solidusio-contrib/solidus_product_assembly/pull/8) ([Sinetheta](https://github.com/Sinetheta))
- Fix a load order issue when redefining inventory validator. [\#7](https://github.com/solidusio-contrib/solidus_product_assembly/pull/7) ([Senjai](https://github.com/Senjai))
- Fix product sub\_menu display on new Solidus [\#6](https://github.com/solidusio-contrib/solidus_product_assembly/pull/6) ([Sinetheta](https://github.com/Sinetheta))
- Inventory validation [\#5](https://github.com/solidusio-contrib/solidus_product_assembly/pull/5) ([Sinetheta](https://github.com/Sinetheta))
- Rename to solidus\_product\_assembly [\#2](https://github.com/solidusio-contrib/solidus_product_assembly/pull/2) ([Sinetheta](https://github.com/Sinetheta))
- Upgrade from spree 2.4 to solidus 1.1-1.3 [\#1](https://github.com/solidusio-contrib/solidus_product_assembly/pull/1) ([Sinetheta](https://github.com/Sinetheta))



\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*