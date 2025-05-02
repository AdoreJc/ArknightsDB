# SquadListItem

**Namespace:** `Torappu.UI.Squad`


## Fields

- `SquadSharedCharHeadIcon _charView`

- `Image _headImage`

- `Text _friendName`

- `Text _friendLvl`

- `Text _serverName`

- `Text _aliasName`

- `Animator _aliasAnim`

- `SquadFriendData m_cacheData`


## Methods

- `Void ApplyData(SquadFriendData, String)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class SquadListItem : MonoBehaviour, IHotfixable
{
	private SquadSharedCharHeadIcon _charView; // 0x18
	private Image _headImage; // 0x20
	private Text _friendName; // 0x28
	private Text _friendLvl; // 0x30
	private Text _serverName; // 0x38
	private Text _aliasName; // 0x40
	private Animator _aliasAnim; // 0x48
	private SquadFriendData m_cacheData; // 0x50
	private static DelegateBridge __Hotfix0_ApplyData; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x23cd530 VA: 0x75949e5530
	public Void ApplyData(SquadFriendData data, String alias) { }
	// RVA: 0x23cda50 VA: 0x75949e5a50
	public Void OnClick() { }
	// RVA: 0x23cdb4c VA: 0x75949e5b4c
	public Void .ctor() { }
}
```