# FunLiveUIBattlePhotoItemAttributeIcon

**Namespace:** `Torappu.Battle.FunLive`


## Fields

- `GameObject _questionMark`

- `GameObject _firstLevel`

- `GameObject _firstLevelDown`

- `GameObject _secondLevel`

- `GameObject _secondLevelDown`

- `Int32 m_attributeDiffNum`

- `FunLiveGameMode m_gameMode`


## Methods

- `Void Awake()`

- `Void SetIconEnable(Boolean)`

- `Void SetIconAttributeLevel(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.FunLive
public class FunLiveUIBattlePhotoItemAttributeIcon : MonoBehaviour, IHotfixable
{
	private GameObject _questionMark; // 0x18
	private GameObject _firstLevel; // 0x20
	private GameObject _firstLevelDown; // 0x28
	private GameObject _secondLevel; // 0x30
	private GameObject _secondLevelDown; // 0x38
	private Int32 m_attributeDiffNum; // 0x40
	private FunLiveGameMode m_gameMode; // 0x48
	private static DelegateBridge __Hotfix0_Awake; // 0x0
	private static DelegateBridge __Hotfix0_SetIconEnable; // 0x8
	private static DelegateBridge __Hotfix0_SetIconAttributeLevel; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1c5ba74 VA: 0x7594273a74
	private Void Awake() { }
	// RVA: 0x1c5b7c4 VA: 0x75942737c4
	public Void SetIconEnable(Boolean enable) { }
	// RVA: 0x1c5b850 VA: 0x7594273850
	public Void SetIconAttributeLevel(Int32 value) { }
	// RVA: 0x1c5bbb0 VA: 0x7594273bb0
	public Void .ctor() { }
}
```