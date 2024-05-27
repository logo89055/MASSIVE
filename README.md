# MASSIVE
Массивы Дан
$arr = array_fill(0, 100, mt_rand(1, 20));
$count = 0;
for ($i = 0; $i < count($arr) - 1; $i++) {
    if ($arr[$i] == $arr[$i + 1]) {
        $count++;
    }
}
echo "Количество последовательных пар одинаковых элементов: " . $count;
