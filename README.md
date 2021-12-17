SELECT Floor FROM DIGITALTWINS Floor Join Facility Related Floor.isPartOf Where Facility.$dtId = 'DunbarHS'

SELECT Space FROM DIGITALTWINS Space Join Floor Related Space.isPartOf Join Facility Related Floor.isPartOf Where Facility.$dtId = 'DunbarHS'
