# <x-trans>Numerals</x-trans>

<x-trans>Zerita is using two parallel number systems, a decimal and a hexadecimal one.</x-trans>
<x-trans>Hexadecimal numbering system is present, for future-proofing purposes.</x-trans>
<x-trans>Both numbering systems use big billions for the naming.</x-trans>

## <x-trans>Numbers and writing</x-trans>

<x-trans>Zerita is using 0-9 and A-F for writing the numbers in hexadecimal, so there is no chance of misunderstanding as words use only lowercase letters to be written.</x-trans>
<x-trans>The preferred grouping for numbers is with an underscore, as it's unambiguous.</x-trans>

<x-trans>The numbers that have a basic name are:</x-trans>

| <x-trans>Decimal</x-trans> | <x-trans>Hexadecimal</x-trans> | <x-trans>Name</x-trans> |
| -------------------------- | ------------------------------ | ----------------------- |
| 0                          | 0x0                            | &{nula}                 |
| 1                          | 0x1                            | &{uno}                  |
| 2                          | 0x2                            | &{dos}                  |
| 3                          | 0x3                            | &{tres}                 |
| 4                          | 0x4                            | &{tetra}                |
| 5                          | 0x5                            | &{pente}                |
| 6                          | 0x6                            | &{ses}                  |
| 7                          | 0x7                            | &{septe}                |
| 8                          | 0x8                            | &{okto}                 |
| 9                          | 0x9                            | &{nove}                 |
| 10                         | 0xA                            | &{deka}                 |
| 11                         | 0xB                            | &{lona}                 |
| 12                         | 0xC                            | &{bili}                 |
| 13                         | 0xD                            | &{san}                  |
| 14                         | 0xE                            | &{dort}                 |
| 15                         | 0xF                            | &{piec}                 |
| 16                         | 0x10                           | &{anim}                 |
| 100                        | 0x64                           | &{sent}                 |
| 256                        | 0x100                          | &{cem}                  |
| 1_000                      | 0x3E8                          | &{mil}                  |
| 4_096                      | 0x1_000                        | &{alf}                  |
| 1_000_000                  | 0xF4_240                       | &{milonu}               |
| 16_777_216                 | 0x1_000_000                    | &{bet}                  |

### <x-trans>Larger numbers</x-trans>

<x-trans>Both systems, after 999_999 are using powers of 1_000_000 to create names for arbitrary large numbers.</x-trans>
<x-trans>For one-word powers, instead of using the form "&{ad X potente}", the ending "&{-ente}" can be used.</x-trans>

### <x-trans>Decimal</x-trans>

The power names

| Decimal           | Name                                      |
| ----------------- | ----------------------------------------- |
| 1_000_000         | &{milonu}                                 |
| 1_000_000_000_000 | &{dosente milonu (milonu ad dos potente)} |

### <x-trans>Hexadecimal</x-trans>

The power names

| Hexadecimal         | Name                                |
| ------------------- | ----------------------------------- |
| 0x1_000_000         | &{bet}                              |
| 0x1_000_000_000_000 | &{dosente bet (bet ad dos potente)} |

## Examples

### <x-trans>Decimal</x-trans>

| <x-trans>Decimal</x-trans> | <x-trans>Name</x-trans>                                                                        |
| -------------------------- | ---------------------------------------------------------------------------------------------- |
| 11                         | &{deka uno}                                                                                    |
| 17                         | &{deka ses}                                                                                    |
| 91                         | &{novedeka uno}                                                                                |
| 16                         | &{anim}                                                                                        |
| 256                        | &{cem}                                                                                         |
| 4_096                      | &{alf}                                                                                         |
| 16_777_216                 | &{bet}                                                                                         |
| 829                        | &{oktosent dosdeka nove}                                                                       |
| 2_419                      | &{dos mil tetrasent deka nove}                                                                 |
| 32_004                     | &{tresdeka dos mil tetra}                                                                      |
| 699_050                    | &{sessent novedeka nove mil pentedeka}                                                         |
| 78_187_493_530             | &{septedeka okto mil sent oktodeka sept milonu tetrasent novedeka tres mil pentesent tresdeka} |

### <x-trans>Hexadecimal</x-trans>

| <x-trans>Hexadecimal</x-trans> | <x-trans>Name</x-trans>                                                          |
| ------------------------------ | -------------------------------------------------------------------------------- |
| 0x11                           | &{anim uno}                                                                      |
| 0x5B                           | &{penteanim lona}                                                                |
| 0x33D                          | &{trescem tresanim san}                                                          |
| 0x973                          | &{novecem sesanim tres}                                                          |
| 0x7_D04                        | &{septe alf sancem tetra}                                                        |
| 0xAA_AAA                       | &{dekanim deka alf dekacem dekanim deka}                                         |
| 0xF4_240                       | &{milonu}                                                                        |
| 0x1_234_567_89A                | &{alf doscem tresanim tetra bet pentacem sesanim sept alf oktocem noveanim deka} |
