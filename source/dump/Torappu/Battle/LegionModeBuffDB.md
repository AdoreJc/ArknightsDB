# LegionModeBuffDB

**Namespace:** `Torappu.Battle`


## Methods

- `Void LoadIfNot(Dictionary`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class LegionModeBuffDB : SimpleKVTable`2
{
	private Dictionary`2 m_professionBuffDetails; // 0x68
	private static DelegateBridge __Hotfix0_GetData; // 0x0
	private static DelegateBridge __Hotfix0_LoadIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1c576e4 VA: 0x759426f6e4
	public static Boolean GetData(String key, out LegionModeProfessionBuffDetail data) { }
	// RVA: 0x1c577a8 VA: 0x759426f7a8
	public Void LoadIfNot(Dictionary`2 dataPartDict) { }
	// RVA: 0x1c57f0c VA: 0x759426ff0c
	protected override Void OnInit() { }
	// RVA: 0x1c57f7c VA: 0x759426ff7c
	public Void .ctor() { }
}
```