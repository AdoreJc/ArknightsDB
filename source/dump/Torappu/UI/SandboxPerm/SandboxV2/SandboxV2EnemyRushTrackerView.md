# SandboxV2EnemyRushTrackerView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SimpleLayoutContent _content`

- `ScrollRect _scrollRect`

- `Boolean m_isInited`

- `Int32 m_cachedEnterSeq`

- `Adapter m_adapter`

- `SandboxV2EnemyRushTrackerViewModel m_cachedViewModel`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2EnemyRushTrackerView : DataBinder`1, IHotfixable
{
	private SimpleLayoutContent _content; // 0x20
	private ScrollRect _scrollRect; // 0x28
	private Boolean m_isInited; // 0x30
	private Int32 m_cachedEnterSeq; // 0x34
	private Adapter m_adapter; // 0x38
	private SandboxV2EnemyRushTrackerViewModel m_cachedViewModel; // 0x40
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2555f88 VA: 0x7594b6df88
	public override Void OnValueChanged(SandboxV2EnemyRushTrackerProperty property) { }
	// RVA: 0x25560b0 VA: 0x7594b6e0b0
	private Void _InitIfNot() { }
	// RVA: 0x255627c VA: 0x7594b6e27c
	public Void .ctor() { }
}
```