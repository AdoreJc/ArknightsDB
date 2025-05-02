# UITopbarStatusRL3

**Namespace:** ` `


## Fields

- `GameObject container`

- `UILifePoint lifePoint`

- `UILifePointRL3 _RL3LifepointMask`

- `Text monsterInfoText`

- `Text expText`

- `UIAtlasImage expImage`

- `Color expTweenColor`

- `Single expTweenTime`

- `UILifeLostGroup lifeLostContainer`

- `Int32 m_cachedFinishedEnemiesCnt`

- `Int32 m_cachedTotalEnemiesCnt`

- `Int32 m_cachedExp`

- `Tween m_tween`

- `Color m_originColor`


## Methods

- `Void InitData(BattleController, Boolean)`

- `Void UpdateData(BattleController, Boolean, Boolean)`

- `Vector3 CalculateExpScreenPos(Camera)`

- `Void _UpdateMonsterInfo(BattleController, Boolean)`

- `Void _UpdateExpInfo(BattleController, Boolean)`

- `Void _OnExpReached(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class UITopbarStatusRL3
{
	public GameObject container; // 0x10
	public UILifePoint lifePoint; // 0x18
	public UILifePointRL3 _RL3LifepointMask; // 0x20
	public Text monsterInfoText; // 0x28
	public Text expText; // 0x30
	public UIAtlasImage expImage; // 0x38
	public Color expTweenColor; // 0x40
	public Single expTweenTime; // 0x50
	public UILifeLostGroup lifeLostContainer; // 0x58
	private Int32 m_cachedFinishedEnemiesCnt; // 0x60
	private Int32 m_cachedTotalEnemiesCnt; // 0x64
	private Int32 m_cachedExp; // 0x68
	private Tween m_tween; // 0x70
	private Color m_originColor; // 0x78


	// RVA: 0x2076e80 VA: 0x759468ee80
	public Void InitData(BattleController controller, Boolean hideLifePoint) { }
	// RVA: 0x2076878 VA: 0x759468e878
	public Void UpdateData(BattleController controller, Boolean hideLifePoint, Boolean force) { }
	// RVA: 0x207748c VA: 0x759468f48c
	public Vector3 CalculateExpScreenPos(Camera uiCam) { }
	// RVA: 0x2077984 VA: 0x759468f984
	private Void _UpdateMonsterInfo(BattleController controller, Boolean force) { }
	// RVA: 0x2077ad8 VA: 0x759468fad8
	private Void _UpdateExpInfo(BattleController controller, Boolean force) { }
	// RVA: 0x2077c5c VA: 0x759468fc5c
	private Void _OnExpReached(Object arg) { }
	// RVA: 0x2077e64 VA: 0x759468fe64
	public Void .ctor() { }
}
```