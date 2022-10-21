using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.IO;
using UnityEngine;

public class StatSaver : MonoBehaviour
{
    

    // Start is called before the first frame update
    void Start()
    {
    try {
    //Pass file path and name to reader
    StreamReader sr = new StreamReader("playerSave.txt");
    // Read the first line of text
    line = sr.ReadLine();
    while (line != null)
    {
        Console.WriteLine(line);
        line = sr.ReadLine();
    }
    sr.Close();
    Console.ReadLine();
    }
    catch (Exception e)
    {
        Console.WriteLine("Exception: " + e.message);
    }
    finally
    {
        Debug.log("Executing finally block");
    }
    }

    // Update is called once per frame
    void Update()
    {
        
    }
}
