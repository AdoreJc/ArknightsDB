# MissionArchivePage

**Namespace:** `Torappu.UI.MissionArchive`


## Fields

- `Transform _controllerContainer`

- `Transform _rtContentContainer`

- `String m_cachedTopicId`

- `MissionArchiveController m_controller`

- `GameObject m_rtContent`


## Methods

- `Void _LoadContentIfNeed()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `Void <>xLuaBaseProxy_OnReuse(DataBundle)`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(Boolean)`

- `IEnumerator <>xLuaBaseProxy_HideCoroutine(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.MissionArchive
public class MissionArchivePage : UIPage, IHotfixable
{
	private Transform _controllerContainer; // 0xd0
	private Transform _rtContentContainer; // 0xd8
	private String m_cachedTopicId; // 0xe0
	private MissionArchiveController m_controller; // 0xe8
	private GameObject m_rtContent; // 0xf0
	private static DelegateBridge __Hotfix0_OnCreate; // 0x0
	private static DelegateBridge __Hotfix0_OnReuse; // 0x8
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x10
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x18
	private static DelegateBridge __Hotfix0__LoadContentIfNeed; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x272c400 VA: 0x7594d44400
	protected override Void OnCreate(DataBundle savedInstance) { }
	// RVA: 0x272c740 VA: 0x7594d44740
	protected override Void OnReuse(DataBundle savedInstance) { }
	// RVA: 0x272c7bc VA: 0x7594d447bc
	public override IEnumerator ShowCoroutine(Boolean isFromStack) { }
	// RVA: 0x272c8ac VA: 0x7594d448ac
	protected override IEnumerator HideCoroutine(Boolean isIntoStack) { }
	// RVA: 0x272c47c VA: 0x7594d4447c
	private Void _LoadContentIfNeed() { }
	// RVA: 0x272c99c VA: 0x7594d4499c
	public Void .ctor() { }
	// RVA: 0x272ca0c VA: 0x7594d44a0c
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x272ca14 VA: 0x7594d44a14
	private Void <>xLuaBaseProxy_OnReuse(DataBundle P0) { }
	// RVA: 0x272ca1c VA: 0x7594d44a1c
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(Boolean P0) { }
	// RVA: 0x272ca28 VA: 0x7594d44a28
	private IEnumerator <>xLuaBaseProxy_HideCoroutine(Boolean P0) { }
}
```