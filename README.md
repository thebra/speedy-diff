speedy-diff
===========

Compare to files with diff and create a file from the difference.

Installation via Composer:

composer require jasonbradley/speedy-diff:dev-master

Usage:

$speedyDiff = new \JasonBradley\SpeedyDiff\SpeedyDiff($file1, $file2);

echo $speedyDiff->getDiffOutput();
