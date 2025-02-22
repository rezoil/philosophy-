using JetBrains.Annotations;
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class poslanie : MonoBehaviour
{
    internal string Нигилизм = "всем интересно, то что";
    public string иплина = "инстина в том,";
    private string Фильтрум = "успех?";
    private string должно = "правда";
    protected string окус = "что все любят сладкую ложь";
    protected string времятикает = "исти .,,";
    private string правда = "ложно";

    public string ХАХА = "и некому неинтересно слушать";
    private void Start()
    {
        сизиф();
    }
    public void сизиф()
    {
        if (Фильтрум == "успех?" || Фильтрум == "не успех ?")
        {
            Debug.Log(окус);
        }
        Debug.Log(ХАХА);
    }
    public void a(string скоро)
    {
        Debug.Log(скоро);
        Debug.Log(Нигилизм);
    }
    Debug.Log(правда + " интересно, а не истино полезно");
    private void Awake()
    {
        Debug.Log(иплина);
        switch (иплина)
        {
            case "дис":
                Debug.Log(Фильтрум);
                break;
            case "инстина в том,":
                Debug.Log(иплина);
                break;
        }
    }
}
