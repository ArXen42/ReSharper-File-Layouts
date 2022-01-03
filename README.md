
# ReSharper file and type layouts

Listed layouts can be loaded into ReSharper by opening Settings -> Code Editing -> C# -> File Layout and clicking "XAML" link at the upper-right corner of designer. Tested with ReSharper 2017.2.

## StyleCop-like/StyleCopExtended.xaml

This layout is aimed to comply with the following [StyleCop rules](https://documentation.help/StyleCop/Ordering%20Rules.html): **SA1201**, **SA1202**, **SA1203**, **SA1204** and **SA1207**. It also does the following:
 - Operators are placed before indexers
 - **Events**, **properties** and **methods** are sorted in the following order: `Static, Access, Abstract, Implements Interface, Virtual, Override, Sealed`. **Indexers** are sorted in the same order but without `Static` entry. This layout does **not** perform alphabetical ordering.
 - Default ReSharper layouts for special file types are left intact.

Links used for reference (this layout is created from scratch and differs from both variants): 
 
 - https://gist.github.com/StevenLiekens/2ff74b148297c8879d3c
 - http://www.levibotelho.com/development/stylecop-type-members-layout-for-resharper/

# Other

Other layouts may be added later, be it modifications of StyleCop ruleset or completely different layouts (members ordering based primarily on access instead of member kind, for example).

Feel free to send pull-request or open an issue for new layout or fix.
