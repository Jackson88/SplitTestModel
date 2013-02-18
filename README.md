SplitTestModel
==============

SplitTestModel class for split testing

config example:

experiments.php:
<?php
return array(
    'Experiment1' => array(
        'Variant1' => 50,
        'Variant2'   => 50
    ),
    'Experiment2' => array(
        'Variant1' => 15,
        'Variant2' => 35,
        'Variant3' => 12,
        'Variant4' => *
    )
);
?>