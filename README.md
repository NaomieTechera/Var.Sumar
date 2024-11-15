using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class NewBehaviourScript : MonoBehaviour
{
    int valor1 = 2;
    int valor2 = 8;

    int resultadosuma;
    // Start is called before the first frame update
    void Start()
    {
        resultadosuma = (valor1 + valor2);

        Debug.Log("la suma de valor2 + valor1 es igual a: " + (valor1 + valor2));
        Debug.Log("la resta de valor2 + valor1 es igual a: " + (valor1 - valor2));
        
    }

    // Update is called once per frame
    void Update()
    {
        
    }
}
