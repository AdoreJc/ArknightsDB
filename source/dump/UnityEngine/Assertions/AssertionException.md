# AssertionException

**Namespace:** `UnityEngine.Assertions`


## Fields

- `String m_UserMessage`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine.Assertions
public class AssertionException : Exception
{
	private String m_UserMessage; // 0x90

	public override String Message { get; }

	// RVA: 0x68a9148 VA: 0x7598ec1148
	public Void .ctor(String message, String userMessage) { }
	// RVA: 0x68a9b68 VA: 0x7598ec1b68
	public override String get_Message() { }
}
```