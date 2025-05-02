# VariableTranslater

**Namespace:** `Torappu.AVG`


## Fields

- `VariableGetterDelegate m_varGetter`


## Methods

- `Boolean TryTranslate(String, out)`

- `String _ParseVariable(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class VariableTranslater : IAVGTextTranslater
{
	private VariableGetterDelegate m_varGetter; // 0x10


	// RVA: 0x3e940c8 VA: 0x75964ac0c8
	public Void .ctor(VariableGetterDelegate varGetter) { }
	// RVA: 0x3e940f8 VA: 0x75964ac0f8
	public Boolean TryTranslate(String content, out String result) { }
	// RVA: 0x3e9434c VA: 0x75964ac34c
	private String _ParseVariable(String varName) { }
}
```