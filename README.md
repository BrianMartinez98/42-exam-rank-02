# 42 Exam Rank 02 — Practice Solutions

Practice repository for **42 Exam Rank 02**. It contains solved C exercises grouped by level, with the original exercise statements kept inside each folder when available.

## Structure

| Level | Included exercises |
|---|---|
| Level 1 | `first_word`, `fizzbuzz`, `ft_putstr`, `ft_strcpy`, `ft_strlen`, `ft_swap`, `repeat_alpha`, `rev_print`, `rot_13`, `rotone`, `search_and_replace`, `ulstr` |
| Level 2 | `alpha_mirror`, `camel_to_snake`, `do_op`, `ft_atoi`, `ft_strcmp`, `ft_strcspn`, `ft_strdup`, `last_word`, `max`, `print_bits`, `reverse_bits`, `snake_to_camel`, `swap_bits` |
| Level 3 | `ft_atoi_base`, `ft_list_size`, `ft_range`, `ft_rrange`, `lcm`, `pgcd`, `tab_mult` |
| Level 4 | `flood_fill`, `fprime`, `ft_itoa`, `ft_split`, `sort_int_tab` |

## Compile check

```bash
./scripts/check.sh
```

The script compiles each `.c` file independently with:

```bash
gcc -Wall -Wextra -Werror -std=c99
```

## Notes

- This is a study/practice repository, not an official 42 resource.
- Some exercises are standalone programs with a `main`; others are functions expected to be tested by an external main.
- The original MIT license notice from the uploaded Rank 02 archive is preserved.
