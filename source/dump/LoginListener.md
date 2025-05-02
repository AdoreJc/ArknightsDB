# LoginListener

**Namespace:** ` `


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LoginListener
{
	public const Single PROG_START; // 0x0
	public const Single PROG_SDK_LOGIN; // 0x0
	public const Single PROG_LOGIN; // 0x0
	public const Single PROG_START_SYNC_DATA; // 0x0
	public const Single PROG_START_CONFIRM_ORDER; // 0x0
	public const Single PROG_FINISH_CONFIRM_ORDER; // 0x0
	public Action`1 onProgress; // 0x10


	// RVA: 0x27b7e5c VA: 0x7594dcfe5c
	public static Void TriggerProgress(LoginListener inst, Single progress) { }
	// RVA: 0x27b7e7c VA: 0x7594dcfe7c
	public Void .ctor() { }
}
```