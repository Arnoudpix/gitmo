# gitmo
#####################
class Color {

    public $color = "";

    function __construct($color) {
        $this->color = $color;
    }

    public function __toString() {
      return $this->color;
    }

}

##########################
