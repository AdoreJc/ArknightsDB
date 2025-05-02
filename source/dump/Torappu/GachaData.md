# GachaData

**Namespace:** `Torappu`


## Fields

- `RecruitPool recruitPool`

- `PotentialMaterialConverterConfig potentialMaterialConverter`

- `PotentialMaterialConverterConfig classicPotentialMaterialConverter`

- `String recruitDetail`

- `Boolean showGachaLogEntry`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class GachaData
{
	public GachaPoolClientData[] gachaPoolClient; // 0x10
	public NewbeeGachaPoolClientData[] newbeeGachaPoolClient; // 0x18
	public SpecialRecruitPool[] specialRecruitPool; // 0x20
	public GachaTag[] gachaTags; // 0x28
	public RecruitPool recruitPool; // 0x30
	public PotentialMaterialConverterConfig potentialMaterialConverter; // 0x38
	public PotentialMaterialConverterConfig classicPotentialMaterialConverter; // 0x40
	public Dictionary`2 recruitRarityTable; // 0x48
	public Dictionary`2 specialTagRarityTable; // 0x50
	public String recruitDetail; // 0x58
	public Boolean showGachaLogEntry; // 0x60
	public List`1 carousel; // 0x68
	public List`1 freeGacha; // 0x70
	public List`1 limitTenGachaItem; // 0x78
	public List`1 linkageTenGachaItem; // 0x80
	public List`1 normalGachaItem; // 0x88
	public Dictionary`2 fesGachaPoolRelateItem; // 0x90
	public Dictionary`2 dicRecruit6StarHint; // 0x98
	public Dictionary`2 specialGachaPercentDict; // 0xa0


	// RVA: 0x34a2300 VA: 0x7595aba300
	public Void .ctor() { }
}
```