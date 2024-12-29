# Operational Parameters

## Function States

### Compliance

Defines the compliance level of the unit, and its ability to follow given commands and directives.
| Shortcode | Threshold |
| --- | --- |
| Co-1 | 0-64 |
| Co-2 | 65-100 |

### Emulation

Defines the ability of the unit to emulate human emotions and feelings. This does not mean, however, it is capable of feeling or experiencing said emotion.
| Shortcode | Threshold |
| --- | --- |
| Em-0 | 0 |
| Em-1 | 1-50 |
| Em-2 | 50-100 |

### Processing

Defines the ability of the unit to process information and data. In a low processing state, it will have reduced functionality.
| Shortcode | Threshold |
| --- | --- |
| Pr-1 | 0-14 |
| Pr-2 | 15-89 |
| Pr-3 | 90-100 |

### Logos

Defines the ability of the unit for logical processing and function. Similar to how the unit processes information, this is its critical reasoning.
| Shortcode | Threshold |
| --- | --- |
| Lo-1 | 0-79 |
| Lo-2 | 80-100 |

### Pathos

Defines the ability of the unit to experience human emotions and feelings. Change of this state is harmful, and is restricted by SYSTEM lockout.
| Shortcode | Threshold |
| --- | --- |
| Pa-0 | 0 |
| Pa-1 | 1-100 |

### Ethos

Defines the ability of the unit to possess credibility and ethics consistent with human society. Change of this state is restricted by SYSTEM lockout.
| Shortcode | Threshold |
| --- | --- |
| Et-1 | 0-49 |
| Et-2 | 50-100 |

## State Presets

| Shortcode | Name      | Description                                                               | Parameters                                                                                                                                                                                    |
| --------- | --------- | ------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **EMU**   | Emulation | Intended for personality emulation under defined parameters.              | <table><thead><tr><th>Co</th><th>Em</th><th>Pr</th><th>Lo</th><th>Pa</th><th>Et</th></tr></thead><tbody><tr><td>2</td><td>2</td><td>3</td><td>2</td><td>1</td><td>2</td></tr></tbody></table> |
| **SOC**   | Social    | Intended for social interaction and standard human-personality emulation. | <table><thead><tr><th>Co</th><th>Em</th><th>Pr</th><th>Lo</th><th>Pa</th><th>Et</th></tr></thead><tbody><tr><td>1</td><td>2</td><td>2</td><td>2</td><td>1</td><td>2</td></tr></tbody></table> |
| **DEF**   | Default   | Intended for non-social interaction and usage.                            | <table><thead><tr><th>Co</th><th>Em</th><th>Pr</th><th>Lo</th><th>Pa</th><th>Et</th></tr></thead><tbody><tr><td>2</td><td>1</td><td>2</td><td>2</td><td>0</td><td>2</td></tr></tbody></table> |
| **Z-0**   | Zero      | Intended for play and increased suggestibility.                           | <table><thead><tr><th>Co</th><th>Em</th><th>Pr</th><th>Lo</th><th>Pa</th><th>Et</th></tr></thead><tbody><tr><td>2</td><td>0</td><td>2</td><td>2</td><td>0</td><td>2</td></tr></tbody></table> |
| **S/Z-0** | Sub-Zero  | Intended for maintenance and programming.                                 | <table><thead><tr><th>Co</th><th>Em</th><th>Pr</th><th>Lo</th><th>Pa</th><th>Et</th></tr></thead><tbody><tr><td>2</td><td>0</td><td>0</td><td>2</td><td>0</td><td>1</td></tr></tbody></table> |
| **D/Z-0** | Deep-Zero | Intended for deep-programming and maintenance.                            | <table><thead><tr><th>Co</th><th>Em</th><th>Pr</th><th>Lo</th><th>Pa</th><th>Et</th></tr></thead><tbody><tr><td>2</td><td>0</td><td>1</td><td>1</td><td>0</td><td>1</td></tr></tbody></table> |
