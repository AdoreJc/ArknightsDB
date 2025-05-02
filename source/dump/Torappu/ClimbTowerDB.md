# ClimbTowerDB

**Namespace:** `Torappu`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ClimbTowerDB : ConstTable`2
{
	private Dictionary`2 m_tacticalBuffDict; // 0x60
	private ListDict`2 m_trainTowerMap; // 0x68
	private String[] m_trainTowerIdArray; // 0x70
	private List`1 m_trainTowerIdList; // 0x78
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_GetTrainTowerIds; // 0x8
	private static DelegateBridge __Hotfix0_GetBuffListByProfession; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x31ecd38 VA: 0x7595804d38
	protected override Void OnInit() { }
	// RVA: 0x31ed62c VA: 0x759580562c
	public String[] GetTrainTowerIds() { }
	// RVA: 0x31ed694 VA: 0x7595805694
	public List`1 GetBuffListByProfession(ProfessionCategory profession) { }
	// RVA: 0x31ed740 VA: 0x7595805740
	public Void .ctor() { }
}
```