# SandboxV2DungeonSphereNormalView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Text _topicName`

- `Text _settleDayTip`

- `Text _seasonName`

- `Text _seasonRemainDay`

- `UIAtlasImage _seasonRemainBkg`

- `Text _desc`

- `Text _functionalDesc`

- `GameObject _panelNormal`

- `GameObject _panelRiftReserve`

- `GameObject _panelArchive`

- `Text _coolDownText`

- `Button _panelArchiveHotspot`

- `GameObject _panelLoadArchive`

- `GameObject _panelDeleteArchive`

- `ScrollRect _scrollRect`

- `GameObject _panelSeason`

- `UIPageFinder m_pageFinder`

- `CountDownTask m_cacheCountDownTask`

- `SandboxV2DungeonViewModel m_cachedViewModel`


## Methods

- `Void Update()`

- `Void Render(SandboxV2DungeonViewModel)`

- `Void OnReserveClick()`

- `Void OnLoadArchiveClick()`

- `Void OnDeleteArchiveClick()`

- `Void TutorialOnly_TryRaiseAVGSignal()`

- `Void <TutorialOnly_TryRaiseAVGSignal>b__24_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonSphereNormalView : MonoBehaviour, IHotfixable
{
	private Text _topicName; // 0x18
	private Text _settleDayTip; // 0x20
	private Text _seasonName; // 0x28
	private Text _seasonRemainDay; // 0x30
	private UIAtlasImage _seasonRemainBkg; // 0x38
	private Text _desc; // 0x40
	private Text _functionalDesc; // 0x48
	private GameObject _panelNormal; // 0x50
	private GameObject _panelRiftReserve; // 0x58
	private GameObject _panelArchive; // 0x60
	private Text _coolDownText; // 0x68
	private Button _panelArchiveHotspot; // 0x70
	private GameObject _panelLoadArchive; // 0x78
	private GameObject _panelDeleteArchive; // 0x80
	private ScrollRect _scrollRect; // 0x88
	private GameObject _panelSeason; // 0x90
	private UIPageFinder m_pageFinder; // 0x98
	private CountDownTask m_cacheCountDownTask; // 0xa8
	private SandboxV2DungeonViewModel m_cachedViewModel; // 0xb0
	private static DelegateBridge __Hotfix0_Update; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_OnReserveClick; // 0x10
	private static DelegateBridge __Hotfix0_OnLoadArchiveClick; // 0x18
	private static DelegateBridge __Hotfix0_OnDeleteArchiveClick; // 0x20
	private static DelegateBridge __Hotfix0_TutorialOnly_TryRaiseAVGSignal; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x255146c VA: 0x7594b6946c
	private Void Update() { }
	// RVA: 0x2550d4c VA: 0x7594b68d4c
	public Void Render(SandboxV2DungeonViewModel viewModel) { }
	// RVA: 0x25514f0 VA: 0x7594b694f0
	public Void OnReserveClick() { }
	// RVA: 0x25515a4 VA: 0x7594b695a4
	public Void OnLoadArchiveClick() { }
	// RVA: 0x2551658 VA: 0x7594b69658
	public Void OnDeleteArchiveClick() { }
	// RVA: 0x2551294 VA: 0x7594b69294
	public Void TutorialOnly_TryRaiseAVGSignal() { }
	// RVA: 0x255170c VA: 0x7594b6970c
	public Void .ctor() { }
	// RVA: 0x255177c VA: 0x7594b6977c
	private Void <TutorialOnly_TryRaiseAVGSignal>b__24_0() { }
}
```