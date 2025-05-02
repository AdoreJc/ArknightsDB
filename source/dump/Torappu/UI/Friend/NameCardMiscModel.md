# NameCardMiscModel

**Namespace:** `Torappu.UI.Friend`


## Fields

- `Boolean showDetail`

- `Boolean showBirth`

- `Boolean birthEnabled`

- `Boolean birthSet`


## Methods

- `Void CopyFrom(NameCardMiscModel, MiscFlag)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardMiscModel : IHotfixable
{
	public Boolean showDetail; // 0x10
	public Boolean showBirth; // 0x11
	public Boolean birthEnabled; // 0x12
	public Boolean birthSet; // 0x13
	private static DelegateBridge __Hotfix0_CopyFrom; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x28c0a84 VA: 0x7594ed8a84
	public Void CopyFrom(NameCardMiscModel other, MiscFlag flag) { }
	// RVA: 0x28b7c2c VA: 0x7594ecfc2c
	public Void .ctor() { }
}
```