2024-07-27 11:22
Tags: [[Game development]]
Linguagem: [[Csharp]]
Bibliotecas: [[Unity]]

# Programando movimento simples para jogos 2d top-down na unity

```c#
public class PlayerScript : MonoBehaviour  
{  
    public Rigidbody2D rigidbody;  
    // Start is called before the first frame update  
    public int movementSpeed = 10;  
    public int jumpBoost = 10;  
    void Start()  
    {            }  
  
    // Update is called once per frame  
    void Update()  
    {        if (Input.GetKey(KeyCode.A))  
        {            rigidbody.transform.position += Vector3.left * movementSpeed * Time.deltaTime;  
        }  
        if (Input.GetKey(KeyCode.D))  
        {            rigidbody.transform.position += Vector3.right * movementSpeed * Time.deltaTime;  
        }  
        if (Input.GetKey(KeyCode.W))  
        {            rigidbody.transform.position += Vector3.up * movementSpeed * Time.deltaTime;  
        }        if (Input.GetKey(KeyCode.S))  
        {            rigidbody.transform.position += Vector3.down * movementSpeed * Time.deltaTime;  
        }    }}
```


# Referencias