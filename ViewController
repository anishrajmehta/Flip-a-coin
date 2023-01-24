import UIKit

class ViewController: UIViewController
{
    
    var tossCountNumber = 0
    
    @IBOutlet weak var tossCount: UILabel!
    @IBOutlet weak var pole: UILabel!
    
    override func viewDidLoad()
    {
        super.viewDidLoad()
        // Do any additional setup after loading the view, typically from a nib.
        
    }
    
    func tossTheCoin()
    {
        
        tossCountNumber += 1
        tossCount.text = "Toss Count: \(tossCountNumber)"
        
        let parity: Bool = Bool.random()
        
        switch parity
        {
        case true: //Heads
            pole.text = "It's Heads"
        case false: //Tails
            pole.text = "It's Tails"
        }
    }
    
    @IBAction func onButtonClick(_ sender: Any)
    {
        tossTheCoin()
    }
}
