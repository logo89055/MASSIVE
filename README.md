# MASSIVE
Массивы Дан
$arr = range(1, 100);
$arr = array_merge(
    array_slice($arr, 0, 5),
    array(-51),
    array_fill(0, 3, 12),
    array(-51)
);

echo "Последовательность: ";
foreach ($arr as $value) {
    echo $value . ", ";
}
