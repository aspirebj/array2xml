# Usage
```
include 'library/array2xml.php
$array = [
    'First node' => [
        'name' => 'Bijaya Oli',
        'address' => 'Bhaktapur'
    ],
    'Second node' => [
        'name' => 'Ugyen Chheda Lama',
        'address' => 'Kathmandu'
    ]
];
```
```
$result = SaffronXmlGenerator::convert($array);
```
## After running this piece of code $result will contain:
```
<?xml version="1.0"?>
<root>
    <First_node>
        <name>Bijaya Oli</name>
        <weapon>Bhaktapur</weapon>
    </First_node>
    <Second_node>
        <name>Ugyen Chheda</name>
        <weapon>Kathmandu</weapon>
    </Second_node>
</root>
```
