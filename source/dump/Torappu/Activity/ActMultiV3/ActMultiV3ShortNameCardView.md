# ActMultiV3ShortNameCardView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Text _doctorLevel`

- `Text _doctorName`

- `GameObject _doctorUidGO`

- `Text _doctorUid`

- `Text _doctorTitle`

- `Image _bgImg`

- `GameObject _mentorObj`

- `GameObject _earlyQuitMaskGO`

- `Transform _avatarViewContainer`

- `PlayerAvatarView m_avatarView`


## Methods

- `Void Render(String, STPlayerStatus, ILoadAsset)`

- `Void Render(ActMultiV3NameCardParam, ILoadAsset)`

- `Void _Render(ActMultiV3NameCardParam, ILoadAsset)`

- `Boolean _CanUidHide()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3ShortNameCardView : MonoBehaviour, IHotfixable
{
	private Text _doctorLevel; // 0x18
	private Text _doctorName; // 0x20
	private GameObject _doctorUidGO; // 0x28
	private Text _doctorUid; // 0x30
	private Text _doctorTitle; // 0x38
	private Image _bgImg; // 0x40
	private GameObject _mentorObj; // 0x48
	private GameObject _earlyQuitMaskGO; // 0x50
	private Transform _avatarViewContainer; // 0x58
	private PlayerAvatarView m_avatarView; // 0x60
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix1_Render; // 0x8
	private static DelegateBridge __Hotfix0__Render; // 0x10
	private static DelegateBridge __Hotfix0__CanUidHide; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x30e42ac VA: 0x75956fc2ac
	public Void Render(String actId, STPlayerStatus playerStatus, ILoadAsset assetLoader) { }
	// RVA: 0x30e473c VA: 0x75956fc73c
	public Void Render(ActMultiV3NameCardParam param, ILoadAsset assetLoader) { }
	// RVA: 0x30e442c VA: 0x75956fc42c
	private Void _Render(ActMultiV3NameCardParam param, ILoadAsset assetLoader) { }
	// RVA: 0x30e47c8 VA: 0x75956fc7c8
	private Boolean _CanUidHide() { }
	// RVA: 0x30e4874 VA: 0x75956fc874
	public Void .ctor() { }
}
```