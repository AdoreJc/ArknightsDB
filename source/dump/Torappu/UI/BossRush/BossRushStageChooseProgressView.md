# BossRushStageChooseProgressView

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `SimpleLayoutContent _progressContent`

- `Boolean m_hasInited`

- `Int32 m_cachedCompleteCount`

- `Int32 m_cachedNormalStageCount`

- `Adapter m_adapter`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushStageChooseProgressView : DataBinder`1, IHotfixable
{
	private SimpleLayoutContent _progressContent; // 0x20
	private Boolean m_hasInited; // 0x28
	private Int32 m_cachedCompleteCount; // 0x2c
	private Int32 m_cachedNormalStageCount; // 0x30
	private Adapter m_adapter; // 0x38
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2e6f9a8 VA: 0x75954879a8
	public override Void OnValueChanged(BossRushStageChooseProperty property) { }
	// RVA: 0x2e6fa6c VA: 0x7595487a6c
	private Void _InitIfNot() { }
	// RVA: 0x2e6fbd0 VA: 0x7595487bd0
	public Void .ctor() { }
}
```