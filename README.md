<div align="center">
  <img src="./white-gorilla.jpg" height="150" alt="Avatar" style="border-radius: 20px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);">
  <h3>👨‍💻 SuanggiLaut.php</h3>
</div>

<br>

```php
<?php

namespace CyberSecurity;

class SuanggiLaut extends PenetrationTester {

    const STATUS = 'Hunting Bugs';
    
    public $skills = [
        'Language' => ['PHP', 'Python', 'Bash'],
        'Tools'    => ['Burp Suite', 'Metasploit', 'Wireshark'],
        'Focus'    => 'Web Application Security'
    ];

    public function __construct() {
        $this->learn("Exploitation");
        $this->collaborate("Open");
    }

    public function getGoal() {
        return "Securing the digital ocean.";
    }
}

// Output: Ready to collaborate
?>
