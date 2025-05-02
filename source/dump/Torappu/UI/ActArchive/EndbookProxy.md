# EndbookProxy

**Namespace:** `Torappu.UI.ActArchive`


## Methods

- `Void _OnEndClicked(ActArchiveType, String)`

- `Void _OnIndexConfirm(ActArchiveType, Int32)`

- `Void _OnEndItemClicked(ActArchiveType, Int32)`

- `Void StartAvgAndBackToArchiveEndbook(StoryData, DataBundle)`

- `UIPageControllerParam _SceneParamToState(DataBundle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class EndbookProxy : ActArchiveCompProxy`1
{
	private static DelegateBridge __Hotfix0_get_compType; // 0x0
	private static DelegateBridge __Hotfix0_GetPrefabPath; // 0x8
	private static DelegateBridge __Hotfix0_InitComp; // 0x10
	private static DelegateBridge __Hotfix0__OnEndClicked; // 0x18
	private static DelegateBridge __Hotfix0__OnIndexConfirm; // 0x20
	private static DelegateBridge __Hotfix0__OnEndItemClicked; // 0x28
	private static DelegateBridge __Hotfix0_StartAvgAndBackToArchiveEndbook; // 0x30
	private static DelegateBridge __Hotfix0__SceneParamToState; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	protected override String compType { get; }

	// RVA: 0x300f160 VA: 0x7595627160
	protected override String get_compType() { }
	// RVA: 0x300f1dc VA: 0x75956271dc
	protected override String GetPrefabPath() { }
	// RVA: 0x300f264 VA: 0x7595627264
	protected override Void InitComp() { }
	// RVA: 0x300f5c8 VA: 0x75956275c8
	private Void _OnEndClicked(ActArchiveType type, String endId) { }
	// RVA: 0x300f6dc VA: 0x75956276dc
	private Void _OnIndexConfirm(ActArchiveType type, Int32 index) { }
	// RVA: 0x300f7f0 VA: 0x75956277f0
	private Void _OnEndItemClicked(ActArchiveType type, Int32 index) { }
	// RVA: 0x300f904 VA: 0x7595627904
	public Void StartAvgAndBackToArchiveEndbook(StoryData targetStory, DataBundle stateBundle) { }
	// RVA: 0x300fae0 VA: 0x7595627ae0
	private UIPageControllerParam _SceneParamToState(DataBundle bundleToState) { }
	// RVA: 0x300fd44 VA: 0x7595627d44
	public Void .ctor() { }
}
```