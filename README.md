# Death-Bunker-Script-Character
Script del personaje 

public class SoldierScript : Monobehaviour {

  private Rigidbody2D myRigidbody;
  private Animator myAnimator;
  private float jumpForce;
  public bool is Alive;
  
  
  void Start () {
    isAlive = true;
    
    myRigidBody = gameObject.GetComponent<RigidBody2D>();
    myAnimator = gameObject.GetComponent<Animator> ();
    
    jumpForce = 10f;
    myRigidBody.gravityScale = 5f;
    
}
