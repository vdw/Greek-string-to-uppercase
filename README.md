# Greek string to uppercase

## A CodeIgniter String Helper that correctly converts greek letters to uppercase
This helper extends the core helper and adds a fuction that converts greek letters of a string to uppercase.

## Usage
Copy *MY_string_helper.php* to *application/helpers* folder.

Load string helper:

    $this->load->helper('string');


Use it:

    $title = 'Τάχιστη αλώπηξ βαφής ψημένη γη - Mary Had A Little Lamb';

    echo grstrtoupper($title);

    // Result
    // ΤΑΧΙΣΤΗ ΑΛΩΠΗΞ ΒΑΦΗΣ ΨΗΜΕΝΗ ΓΗ - MARY HAD A LITTLE LAMB

## Copyright and license

Copyright (©) 2012 Dimitris Krestos. See LICENSE for details.