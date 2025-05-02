# FunLiveUIBattleTopBar

**Namespace:** `Torappu.Battle.FunLive`


## Fields

- `Text _remainTimeText`

- `GameObject _blueBackground`

- `GameObject _redBackground`

- `Text _photoCnt`

- `Sprite _sysMenuButton`

- `Button _photoLibButton`

- `UIAtlasImage _panelImage`

- `Single _tweenTime`

- `Color _tweenColor`

- `Int32 m_remainTime`

- `Color m_originColor`

- `Tween m_tween`

- `FunLiveUIPlugin m_plugin`

- `FunLiveGameMode m_gameMode`


## Methods

- `Void InitData(BattleController, FunLiveUIPlugin)`

- `Void UpdateData(BattleController)`

- `Void _SetRemainTimeInfo()`

- `Void _OnPhotoShoted(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.FunLive
public class FunLiveUIBattleTopBar : MonoBehaviour, IHotfixable
{
	private Text _remainTimeText; // 0x18
	private GameObject _blueBackground; // 0x20
	private GameObject _redBackground; // 0x28
	private Text _photoCnt; // 0x30
	private Sprite _sysMenuButton; // 0x38
	private Button _photoLibButton; // 0x40
	private UIAtlasImage _panelImage; // 0x48
	private Single _tweenTime; // 0x50
	private Color _tweenColor; // 0x54
	private Int32 m_remainTime; // 0x64
	private Color m_originColor; // 0x68
	private Tween m_tween; // 0x78
	private FunLiveUIPlugin m_plugin; // 0x80
	private FunLiveGameMode m_gameMode; // 0x88
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_UpdateData; // 0x8
	private static DelegateBridge __Hotfix0__SetRemainTimeInfo; // 0x10
	private static DelegateBridge __Hotfix0__OnPhotoShoted; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1c5c644 VA: 0x7594274644
	public Void InitData(BattleController controller, FunLiveUIPlugin plugin) { }
	// RVA: 0x1c5ca0c VA: 0x7594274a0c
	public Void UpdateData(BattleController controller) { }
	// RVA: 0x1c5cc1c VA: 0x7594274c1c
	private Void _SetRemainTimeInfo() { }
	// RVA: 0x1c5ced8 VA: 0x7594274ed8
	private Void _OnPhotoShoted(Object arg) { }
	// RVA: 0x1c5d124 VA: 0x7594275124
	public Void .ctor() { }
}
```