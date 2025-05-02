# CharCardData

**Namespace:** ` `


## Fields

- `String charCardId`

- `Int32 sortIndex`

- `String avgChar`

- `Single avgCharOffsetY`

- `String charCardName`

- `String charCardItaName`

- `String charCardTitle`

- `String charCardDesc`

- `String fullCompleteDes`

- `String gainDesc`

- `String themeColor`

- `String operaItemId`

- `CardGainType gainType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CharCardData
{
	public String charCardId; // 0x10
	public Int32 sortIndex; // 0x18
	public String avgChar; // 0x20
	public Single avgCharOffsetY; // 0x28
	public String charCardName; // 0x30
	public String charCardItaName; // 0x38
	public String charCardTitle; // 0x40
	public String charCardDesc; // 0x48
	public String fullCompleteDes; // 0x50
	public String gainDesc; // 0x58
	public String themeColor; // 0x60
	public List`1 taskRingList; // 0x68
	public String operaItemId; // 0x70
	public CardGainType gainType; // 0x78
	public List`1 gainParamList; // 0x80


	// RVA: 0x33b5d9c VA: 0x75959cdd9c
	public virtual Boolean ShouldSerializegainType() { }
	// RVA: 0x33b5dac VA: 0x75959cddac
	public virtual Boolean ShouldSerializegainParam() { }
	// RVA: 0x33b5dbc VA: 0x75959cddbc
	public Void .ctor() { }
}
```