# Begining
## Использование
Переменная

⠀Чаще всего переменные используются в качестве текста в различных командах. Для использования переменной необходимо поставить знак $, а затем название переменной. Зачастую название заключается в фигурные скобки для того, чтобы переменная не сливалась с последующим текстом
```markdown
variable="value"
echo "$variable"
value
umee_wallet_name="umee"
umeed keys show "$umee_wallet_name"
```
## Аналогично
```markdown
umeed keys show "umee"
dir="dir1/dir2/"
cd "$HOME/${dir}my_dir"

