# CrisisV2AchievementPageGroupView

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `SimpleLayoutContent _content`

- `Boolean m_hasInited`

- `Int32 m_cachedTotalCount`

- `Int32 m_cachedSelectedIndex`

- `Adapter m_adapter`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2AchievementPageGroupView : DataBinder`1, IHotfixable
{
	private SimpleLayoutContent _content; // 0x20
	private Boolean m_hasInited; // 0x28
	private Int32 m_cachedTotalCount; // 0x2c
	private Int32 m_cachedSelectedIndex; // 0x30
	private Adapter m_adapter; // 0x38
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2bf90b0 VA: 0x75952110b0
	public override Void OnValueChanged(CrisisV2AchievementProperty property) { }
	// RVA: 0x2bf91b8 VA: 0x75952111b8
	private Void _InitIfNot() { }
	// RVA: 0x2bf931c VA: 0x759521131c
	public Void .ctor() { }
}
```