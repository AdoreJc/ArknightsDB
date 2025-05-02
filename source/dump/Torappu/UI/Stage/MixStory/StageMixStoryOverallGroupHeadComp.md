# StageMixStoryOverallGroupHeadComp

**Namespace:** `Torappu.UI.Stage.MixStory`


## Fields

- `GameObject _storylinePanel`

- `UIDynImage _storylineAbbrImage`

- `Text _storylineNameText`

- `GameObject _releaseYearPanel`

- `Text _releaseYearText`

- `Single _height`

- `Boolean m_hasInited`

- `ILoadAsset m_iLoadAsset`

- `String m_loadedAbbrIconId`


## Methods

- `Void _Render(ViewModel)`

- `Void InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.MixStory
public class StageMixStoryOverallGroupHeadComp : MonoBehaviour, IHotfixable
{
	private GameObject _storylinePanel; // 0x18
	private UIDynImage _storylineAbbrImage; // 0x20
	private Text _storylineNameText; // 0x28
	private GameObject _releaseYearPanel; // 0x30
	private Text _releaseYearText; // 0x38
	private Single _height; // 0x40
	private Boolean m_hasInited; // 0x44
	private ILoadAsset m_iLoadAsset; // 0x48
	private String m_loadedAbbrIconId; // 0x50
	private static DelegateBridge __Hotfix0__Render; // 0x0
	private static DelegateBridge __Hotfix0_InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2ff9238 VA: 0x7595611238
	private Void _Render(ViewModel model) { }
	// RVA: 0x2ff93a4 VA: 0x75956113a4
	private Void InitIfNot() { }
	// RVA: 0x2ff9450 VA: 0x7595611450
	public Void .ctor() { }
}
```