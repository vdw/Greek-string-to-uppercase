# CodeIgniter String Helpers - Greek string to uppercase

## Correctly converts greek letters to uppercase
This helper extends the core helper and adds a fuction that converts greek letters of a string to uppercase.

## Usage
Copy *MY_string_helper.php* to *application/helpers* folder.

Load array helper:

    $this->load->helper('string');


Use it:

    $title = 'Τάχιστη αλώπηξ βαφής ψημένη γη - Mary Had A Little Lamb';

    grstrtoupper($title);