
#### [Current]
 * 2017-02-09 [d69acfa](../../commit/d69acfa) - __(Denis Korobicyn)__ Release 0.4.0.1
 * 2016-12-14 [825e6e6](../../commit/825e6e6) - __(Artem Napolskih)__ Update active_record.rb
 * 2016-12-14 [d963e0d](../../commit/d963e0d) - __(Artem Napolskih)__ Update state_machines-activerecord.gemspec

#### v0.4.0
 * 2016-05-17 [29a8a8f](../../commit/29a8a8f) - __(Rafael Mendonça França)__ Release 0.4.0
 * 2016-05-17 [5cde2b6](../../commit/5cde2b6) - __(Rafael Mendonça França)__ Allow and test against Rails 5

#### v0.4.0.pre
 * 2015-12-19 [e4f90cd](../../commit/e4f90cd) - __(Abdelkader Boudih)__ version pre release
 * 2015-11-24 [769679f](../../commit/769679f) - __(Olivier Lacan)__ Move declaration of ActiveRecord deps higher
 * 2015-11-24 [57bac4a](../../commit/57bac4a) - __(Olivier Lacan)__ Use SVG Code Climate badge
 * 2015-08-17 [3de5d66](../../commit/3de5d66) - __(Carles Jove i Buxeda)__ Update home page URL
 * 2015-06-19 [a2e35af](../../commit/a2e35af) - __(Thomas Walpole)__ allow for use and testing with activerecord edge (5.0) before 5.0 is released

#### v0.3.0
 * 2015-07-13 [c396b37](../../commit/c396b37) - __(Rafael Mendonça França)__ Release 0.3.0
 * 2015-06-18 [0504224](../../commit/0504224) - __(Kevin Ross)__ bump state_machines-activemodel to >= 0.3.0 to get state_machines 0.4.0
 * 2015-06-17 [33c3f69](../../commit/33c3f69) - __(Kevin Ross)__ Working on #26, added some tests to more clearly establish the baseline, as well as to show that we aren't behaving as expected when considering "ActiveRecord::Base#save returns nil on a rolled-back transaction"
 * 2015-06-17 [c450a55](../../commit/c450a55) - __(Kevin Ross)__ Fixed broken tests from pull #18.  I believe these assertions to be correct and I have been using the behavior asserted by this code for some time.
 * 2015-05-08 [843889e](../../commit/843889e) - __(Tomasz Stachewicz)__ update homepage in gemspec
 * 2015-04-29 [93486c7](../../commit/93486c7) - __(Kevin Ross)__ bump state_machines-activemodel to ~>0.2.0
 * 2015-04-24 [24e7a4b](../../commit/24e7a4b) - __(Kevin Ross)__ #around_save should not be determining the use of transactions.   The TransitionCollection will apply a transaction if configured by the state_machine.use_transaction.
 * 2015-04-24 [c23321a](../../commit/c23321a) - __(Kevin Ross)__ default use_transactions to true
 * 2015-03-25 [a3466b7](../../commit/a3466b7) - __(Kevin Ross)__ Add sample scope usage
 * 2015-02-01 [e6882c9](../../commit/e6882c9) - __(Abdelkader Boudih)__ update API
 * 2015-01-29 [a9860c4](../../commit/a9860c4) - __(Abdelkader Boudih)__ first stable version
 * 2015-01-29 [bf4caea](../../commit/bf4caea) - __(Washington Luiz)__ Make ar 4.1 compatible with latest `state_machines` api
 * 2015-01-28 [93c5f78](../../commit/93c5f78) - __(Washington Luiz)__ Drop support for ar state attributes on the fly
 * 2015-01-26 [eed79a0](../../commit/eed79a0) - __(Washington Luiz)__ Drop `initialize_state` override
 * 2015-01-26 [58ab02a](../../commit/58ab02a) - __(Washington Luiz)__ Pass list of attributes to `initialize_states`
 * 2015-01-21 [9b1f27a](../../commit/9b1f27a) - __(Abdelkader Boudih)__ Fix tests [WIP]
 * 2015-01-19 [08c7881](../../commit/08c7881) - __(Josef Šimánek)__ Remove jruby-19mode from CI.
 * 2015-01-17 [0b1ad20](../../commit/0b1ad20) - __(Washington Luiz)__ Rework initialization for activerecord 4.2
 * 2015-01-17 [041af9e](../../commit/041af9e) - __(Abdelkader Boudih)__ add rake tasks
 * 2015-01-16 [6fd9320](../../commit/6fd9320) - __(Abdelkader Boudih)__ Let break the build.
 * 2015-01-16 [ceef309](../../commit/ceef309) - __(Abdelkader Boudih)__ fixed test
 * 2015-01-06 [3aeb3b3](../../commit/3aeb3b3) - __(Abdelkader Boudih)__ rbx sqlite3 adapter
 * 2015-01-06 [bc63f8f](../../commit/bc63f8f) - __(Abdelkader Boudih)__ jruby sqlite3 adapter
 * 2015-01-06 [b817161](../../commit/b817161) - __(Abdelkader Boudih)__ add badges.
 * 2015-01-06 [89c1253](../../commit/89c1253) - __(Abdelkader Boudih)__ initial import

#### v0.1.2
 * 2015-02-04 [98bedf9](../../commit/98bedf9) - __(Abdelkader Boudih)__ relax ruby version to support jruby until 9000 release

#### v0.1.1
 * 2015-02-01 [4bed1bb](../../commit/4bed1bb) - __(Abdelkader Boudih)__ version bump
 * 2015-02-01 [1ef8652](../../commit/1ef8652) - __(Washington Luiz)__ Pass initialized attributes to state_machines
 * 2015-01-31 [8c44e58](../../commit/8c44e58) - __(Abdelkader Boudih)__ update API
 * 2015-01-20 [0e1740b](../../commit/0e1740b) - __(Abdelkader Boudih)__ Fix incorrect test, cleanup
 * 2015-01-04 [b000808](../../commit/b000808) - __(Abdelkader Boudih)__ ignore jruby for now.
 * 2015-01-04 [3a1b960](../../commit/3a1b960) - __(Abdelkader Boudih)__ remove lock
 * 2015-01-04 [536a357](../../commit/536a357) - __(Abdelkader Boudih)__ fix links
 * 2015-01-04 [5956014](../../commit/5956014) - __(Abdelkader Boudih)__ v 0.0.3
 * 2014-05-17 [fcf517d](../../commit/fcf517d) - __(Abdelkader Boudih)__ Add ruby-head to the build matrix.
 * 2014-05-14 [114298f](../../commit/114298f) - __(Abdelkader Boudih)__ Stripped out observers to their own gem
 * 2014-04-29 [8692263](../../commit/8692263) - __(Abdelkader Boudih)__ Typo in readme
 * 2014-04-29 [a716b83](../../commit/a716b83) - __(Abdelkader Boudih)__ added badges and ruby version dependency
 * 2014-04-29 [c78bba2](../../commit/c78bba2) - __(Abdelkader Boudih)__ first commit

#### v0.2.0
 * 2015-02-01 [e6882c9](../../commit/e6882c9) - __(Abdelkader Boudih)__ update API

#### v0.1.0
 * 2015-01-29 [a9860c4](../../commit/a9860c4) - __(Abdelkader Boudih)__ first stable version
 * 2015-01-29 [bf4caea](../../commit/bf4caea) - __(Washington Luiz)__ Make ar 4.1 compatible with latest `state_machines` api
 * 2015-01-28 [93c5f78](../../commit/93c5f78) - __(Washington Luiz)__ Drop support for ar state attributes on the fly
 * 2015-01-26 [eed79a0](../../commit/eed79a0) - __(Washington Luiz)__ Drop `initialize_state` override
 * 2015-01-26 [58ab02a](../../commit/58ab02a) - __(Washington Luiz)__ Pass list of attributes to `initialize_states`
 * 2015-01-21 [9b1f27a](../../commit/9b1f27a) - __(Abdelkader Boudih)__ Fix tests [WIP]
 * 2015-01-19 [08c7881](../../commit/08c7881) - __(Josef Šimánek)__ Remove jruby-19mode from CI.
 * 2015-01-17 [0b1ad20](../../commit/0b1ad20) - __(Washington Luiz)__ Rework initialization for activerecord 4.2

#### v0.0.1
 * 2015-01-17 [041af9e](../../commit/041af9e) - __(Abdelkader Boudih)__ add rake tasks
 * 2015-01-16 [6fd9320](../../commit/6fd9320) - __(Abdelkader Boudih)__ Let break the build.
 * 2015-01-16 [ceef309](../../commit/ceef309) - __(Abdelkader Boudih)__ fixed test
 * 2015-01-06 [3aeb3b3](../../commit/3aeb3b3) - __(Abdelkader Boudih)__ rbx sqlite3 adapter
 * 2015-01-06 [bc63f8f](../../commit/bc63f8f) - __(Abdelkader Boudih)__ jruby sqlite3 adapter
 * 2015-01-06 [b817161](../../commit/b817161) - __(Abdelkader Boudih)__ add badges.
 * 2015-01-06 [89c1253](../../commit/89c1253) - __(Abdelkader Boudih)__ initial import

#### v0.0.3
 * 2015-01-04 [b000808](../../commit/b000808) - __(Abdelkader Boudih)__ ignore jruby for now.
 * 2015-01-04 [3a1b960](../../commit/3a1b960) - __(Abdelkader Boudih)__ remove lock
 * 2015-01-04 [536a357](../../commit/536a357) - __(Abdelkader Boudih)__ fix links
 * 2015-01-04 [5956014](../../commit/5956014) - __(Abdelkader Boudih)__ v 0.0.3
 * 2014-05-17 [fcf517d](../../commit/fcf517d) - __(Abdelkader Boudih)__ Add ruby-head to the build matrix.
 * 2014-05-14 [114298f](../../commit/114298f) - __(Abdelkader Boudih)__ Stripped out observers to their own gem
 * 2014-04-29 [8692263](../../commit/8692263) - __(Abdelkader Boudih)__ Typo in readme
 * 2014-04-29 [a716b83](../../commit/a716b83) - __(Abdelkader Boudih)__ added badges and ruby version dependency
 * 2014-04-29 [c78bba2](../../commit/c78bba2) - __(Abdelkader Boudih)__ first commit
