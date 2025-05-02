# SandboxV2QuestTrackerView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SimpleLayoutContent _content`

- `ScrollRect _scrollRect`

- `Boolean m_isInited`

- `Int32 m_cachedEnterSeq`

- `Adapter m_adapter`

- `UIStateFinder m_stateFinder`

- `SandboxV2QuestTrackerViewModel m_cachedViewModel`


## Methods

- `Void _InitIfNot()`

- `Void OnOpenArchive()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2QuestTrackerView : DataBinder`1, IHotfixable
{
	private SimpleLayoutContent _content; // 0x20
	private ScrollRect _scrollRect; // 0x28
	private Boolean m_isInited; // 0x30
	private Int32 m_cachedEnterSeq; // 0x34
	private Adapter m_adapter; // 0x38
	private UIStateFinder m_stateFinder; // 0x40
	private SandboxV2QuestTrackerViewModel m_cachedViewModel; // 0x50
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnOpenArchive; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x25584b0 VA: 0x7594b704b0
	public override Void OnValueChanged(SandboxV2QuestTrackerProperty property) { }
	// RVA: 0x25585d8 VA: 0x7594b705d8
	private Void _InitIfNot() { }
	// RVA: 0x25587a4 VA: 0x7594b707a4
	public Void OnOpenArchive() { }
	// RVA: 0x2558858 VA: 0x7594b70858
	public Void .ctor() { }
}
```