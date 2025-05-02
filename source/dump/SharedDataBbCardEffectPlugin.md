# SharedDataBbCardEffectPlugin

**Namespace:** ` `


## Fields

- `SharedDataBbModifier m_dataModifier`

- `Animation m_cardEffectAnimation`


## Methods

- `Void SetData(CardHoldDataModifier)`

- `Void _UpdateEffect()`

- `Void <>xLuaBaseProxy_OnAttach(UICardEffectHolder)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SharedDataBbCardEffectPlugin : CardEffectPlugin
{
	private SharedDataBbModifier m_dataModifier; // 0x30
	private Animation m_cardEffectAnimation; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_SetData; // 0x8
	private static DelegateBridge __Hotfix0_OnAttach; // 0x10
	private static DelegateBridge __Hotfix0_OnTick; // 0x18
	private static DelegateBridge __Hotfix0__UpdateEffect; // 0x20


	// RVA: 0x1b805bc VA: 0x75941985bc
	public Void .ctor(RectTransform pluginPrefab) { }
	// RVA: 0x1b80644 VA: 0x7594198644
	public Void SetData(CardHoldDataModifier modifier) { }
	// RVA: 0x1b80d80 VA: 0x7594198d80
	protected override Void OnAttach(UICardEffectHolder holder) { }
	// RVA: 0x1b80f7c VA: 0x7594198f7c
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1b80e3c VA: 0x7594198e3c
	private Void _UpdateEffect() { }
	// RVA: 0x1b80ff8 VA: 0x7594198ff8
	private Void <>xLuaBaseProxy_OnAttach(UICardEffectHolder P0) { }
	// RVA: 0x1b81000 VA: 0x7594199000
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```