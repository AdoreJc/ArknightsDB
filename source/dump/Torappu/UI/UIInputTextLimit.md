# UIInputTextLimit

**Namespace:** `Torappu.UI`


## Fields

- `Int32 _limitCount`

- `InputField _targetInput`

- `StringBuilder m_sharedBuilder`


## Properties

- `Int32 _MaxTextCount`


## Methods

- `Int32 get__MaxTextCount()`

- `Void OnValueChanged(String)`

- `Boolean _LimitText(String, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIInputTextLimit : MonoBehaviour
{
	private Int32 _limitCount; // 0x18
	private InputField _targetInput; // 0x20
	private StringBuilder m_sharedBuilder; // 0x28

	private Int32 _MaxTextCount { get; }

	// RVA: 0x21d849c VA: 0x75947f049c
	private Int32 get__MaxTextCount() { }
	// RVA: 0x21d84b0 VA: 0x75947f04b0
	public Void OnValueChanged(String curText) { }
	// RVA: 0x21d84f0 VA: 0x75947f04f0
	private Boolean _LimitText(String text, out String newText) { }
	// RVA: 0x21d86b4 VA: 0x75947f06b4
	private static Int32 _CalcCharCount(Char c) { }
	// RVA: 0x21d86f4 VA: 0x75947f06f4
	public Void .ctor() { }
}
```