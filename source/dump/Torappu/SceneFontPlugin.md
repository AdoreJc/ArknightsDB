# SceneFontPlugin

**Namespace:** `Torappu`


## Fields

- `FontSelect _fontSel`


## Methods

- `Void TryAddToSceneFontHolder()`

- `Void UnRegisterFontHolder()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SceneFontPlugin : SingletonMonoBehaviour`1, ISingletonNotAutoCreate
{
	private FontSelect _fontSel; // 0x18
	private static DelegateBridge __Hotfix0_TryAddToSceneFontHolder; // 0x0
	private static DelegateBridge __Hotfix0_UnRegisterFontHolder; // 0x8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3106428 VA: 0x759571e428
	public Void TryAddToSceneFontHolder() { }
	// RVA: 0x3106504 VA: 0x759571e504
	public Void UnRegisterFontHolder() { }
	// RVA: 0x31065dc VA: 0x759571e5dc
	protected override Void OnDestroy() { }
	// RVA: 0x3106664 VA: 0x759571e664
	public Void .ctor() { }
}
```