# SandboxV2NodePreviewNodeBuffView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Image _nodeBuffIcon`

- `GameObject _nodeBuffPanel`

- `SandboxV2NodePreviewNodeBuffFloatPanel _nodeBuffFloatPanel`

- `UIPageFinder m_finder`

- `SandboxV2DungeonNodeBuffViewModel m_cachedModel`


## Methods

- `Void OnBtnZoneBuffDetailClicked()`

- `Void Render(String, SandboxV2DungeonNodeBuffViewModel)`

- `Void CloseZoneBuffDetail()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2NodePreviewNodeBuffView : MonoBehaviour, IHotfixable
{
	private Image _nodeBuffIcon; // 0x18
	private GameObject _nodeBuffPanel; // 0x20
	private SandboxV2NodePreviewNodeBuffFloatPanel _nodeBuffFloatPanel; // 0x28
	private UIPageFinder m_finder; // 0x30
	private SandboxV2DungeonNodeBuffViewModel m_cachedModel; // 0x40
	private static DelegateBridge __Hotfix0_OnBtnZoneBuffDetailClicked; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_CloseZoneBuffDetail; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x256daac VA: 0x7594b85aac
	public Void OnBtnZoneBuffDetailClicked() { }
	// RVA: 0x256db58 VA: 0x7594b85b58
	public Void Render(String topicId, SandboxV2DungeonNodeBuffViewModel viewModel) { }
	// RVA: 0x256dca4 VA: 0x7594b85ca4
	public Void CloseZoneBuffDetail() { }
	// RVA: 0x256dd1c VA: 0x7594b85d1c
	public Void .ctor() { }
}
```