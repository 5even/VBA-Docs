---
title: Recordset (ADO for Visual C++ syntax)
ms.prod: access
ms.assetid: 9abd27de-9794-eb50-9744-1c0dfc13c98b
ms.date: 10/12/2018
ms.localizationpriority: medium
---

# Recordset (ADO for Visual C++ syntax) 

**Applies to:** Access 2013 | Access 2016

## Methods

- [AddNew](https://msdn.microsoft.com/library/bae09be0-5707-4f38-9c74-0acd0f29dbac%28Office.15%29.aspx) (VARIANT  _FieldList,_ VARIANT _Values_)
- [Cancel](https://msdn.microsoft.com/library/747edc04-a5cc-3631-2d0b-82e7e41a76b7%28Office.15%29.aspx) (void)
- [CancelBatch](https://msdn.microsoft.com/library/be7bf073-ed0b-e24c-7ec0-b7379236782a%28Office.15%29.aspx) (AffectEnum  _AffectRecords_)
- [CancelUpdate](https://msdn.microsoft.com/library/2bd4d168-ba52-7786-5046-44febeda88e1%28Office.15%29.aspx) (void)
- [Clone](https://msdn.microsoft.com/library/ca9b2b76-90bf-9a60-2611-3cb4977d5591%28Office.15%29.aspx) (LockTypeEnum  _LockType,_ _ADORecordset ** _ppvObject_)
- [Close](https://msdn.microsoft.com/library/26a7cced-ebeb-70be-f5de-96a35711bc37%28Office.15%29.aspx) (void)
- [CompareBookmarks](https://msdn.microsoft.com/library/826cb3c7-2f5c-284f-421d-6b7b07f14dec%28Office.15%29.aspx) (VARIANT  _Bookmark1_, VARIANT _Bookmark2_, CompareEnum * _pCompare_)
- [Delete](https://msdn.microsoft.com/library/62c39b4d-223e-7b48-6780-6cd272e3114e%28Office.15%29.aspx) (AffectEnum  _AffectRecords_)
- [Find](https://msdn.microsoft.com/library/a7cc9ceb-fdb9-73e2-8328-70b174f93cda%28Office.15%29.aspx) (BSTR  _Criteria,_ LONG _SkipRecords,_ SearchDirectionEnum _SearchDirection,_ VARIANT _Start_)
- [GetRows](https://msdn.microsoft.com/library/570e6f1c-c17a-7d9a-c172-387894a3a1f1%28Office.15%29.aspx) (long  _Rows,_ VARIANT _Start,_ VARIANT _Fields,_ VARIANT * _pvar_)
- [GetString](https://msdn.microsoft.com/library/f496305e-a1f5-7014-7808-7e4961e5f0fa%28Office.15%29.aspx) (StringFormatEnum  _StringFormat,_ long _NumRows,_ BSTR _ColumnDelimeter,_ BSTR _RowDelimeter,_ BSTR _NullExpr,_ BSTR * _pRetString_)
- [Move](https://msdn.microsoft.com/library/1f858654-5fa3-273d-7cdc-574c5f09a420%28Office.15%29.aspx) (long  _NumRecords,_ VARIANT _Start_)
- [MoveFirst](https://msdn.microsoft.com/library/d04ce41c-77c9-df42-115a-65c50a38518a%28Office.15%29.aspx) (void)
- [MoveLast](https://msdn.microsoft.com/library/d04ce41c-77c9-df42-115a-65c50a38518a%28Office.15%29.aspx) (void)
- [MoveNext](https://msdn.microsoft.com/library/d04ce41c-77c9-df42-115a-65c50a38518a%28Office.15%29.aspx) (void)
- [MovePrevious](https://msdn.microsoft.com/library/d04ce41c-77c9-df42-115a-65c50a38518a%28Office.15%29.aspx) (void)
- [NextRecordset](https://msdn.microsoft.com/library/d2776dd5-d521-c57f-dbe5-e02ee238104d%28Office.15%29.aspx) (VARIANT * _RecordsAffected,_ _ADORecordset ** _ppiRs_)
- [Open](https://msdn.microsoft.com/library/87ef19a4-28e1-dec7-ed33-4ae500b9c460%28Office.15%29.aspx) (VARIANT  _Source,_ VARIANT _ActiveConnection,_ CursorTypeEnum _CursorType,_ LockTypeEnum _LockType,_ LONG _Options_)
- [Requery](https://msdn.microsoft.com/library/1062d907-979f-020a-b2ed-94e11c0e7d08%28Office.15%29.aspx) (LONG  _Options_)
- [Resync](https://msdn.microsoft.com/library/f594a200-56e6-fcf5-9b0a-900c56377f24%28Office.15%29.aspx) (AffectEnum  _AffectRecords,_ ResyncEnum _ResyncValues_)
- [Save](https://msdn.microsoft.com/library/02dab13b-f947-b96d-46ea-0def3ed8f28f%28Office.15%29.aspx) (BSTR  _FileName,_ PersistFormatEnum _PersistFormat_)
- [Supports](https://msdn.microsoft.com/library/2b4062ce-44df-4e84-1ce9-d6618c10c2af%28Office.15%29.aspx) (CursorOptionEnum  _CursorOptions,_ VARIANT_BOOL * _pb_)
- [Update](https://msdn.microsoft.com/library/fc88cab6-c379-bb4f-530c-da08107924e0%28Office.15%29.aspx) (VARIANT  _Fields,_ VARIANT _Values_)
- [UpdateBatch](https://msdn.microsoft.com/library/69e72a65-b637-36fd-d09f-7f81050f71ad%28Office.15%29.aspx) (AffectEnum  _AffectRecords_)


## Properties

- [get_AbsolutePage](https://msdn.microsoft.com/library/b6e5daac-cc21-0aa6-9119-a973595762bb%28Office.15%29.aspx) (PositionEnum * _pl_) **put_AbsolutePage** (PositionEnum _Page_)
- [get_AbsolutePosition](https://msdn.microsoft.com/library/500be001-9fa1-177b-f19d-acf003a0cdc2%28Office.15%29.aspx) (PositionEnum * _pl_) **put_AbsolutePosition** (PositionEnum _Position_)
- [get_ActiveCommand](https://msdn.microsoft.com/library/41c19008-cbf7-ade9-b4ab-e908a16784ac%28Office.15%29.aspx) (IDispatch ** _ppCmd_)
- [get_ActiveConnection](https://msdn.microsoft.com/library/5501b2d7-b62c-5fff-1edd-2b7efb3f8c4a%28Office.15%29.aspx) (VARIANT * _pvar_) **put_ActiveConnection** (VARIANT _vConn_) **putref_ActiveConnection** (IDispatch * _pconn_)
- [get_BOF](https://msdn.microsoft.com/library/f797e140-5572-1a4d-9afc-285f6a3868a8%28Office.15%29.aspx) (VARIANT_BOOL * _pb_)
- [get_Bookmark](https://msdn.microsoft.com/library/101b2ce1-21d8-aa79-e530-20f9d1c73fc8%28Office.15%29.aspx) (VARIANT * _pvBookmark_) **put_Bookmark** (VARIANT _vBookmark_)
- [get_CacheSize](https://msdn.microsoft.com/library/42f86cc0-30dc-669b-9e65-5e7ecd52c4d7%28Office.15%29.aspx) (long * _pl_) **put_CacheSize** (long _CacheSize_)
- [get_CursorLocation](https://msdn.microsoft.com/library/8a048bd4-ae25-a555-1c07-14364b7e6560%28Office.15%29.aspx) (CursorLocationEnum * _plCursorLoc_) **put_CursorLocation** (CursorLocationEnum _lCursorLoc_)
- [get_CursorType](https://msdn.microsoft.com/library/f42ded8f-9f92-ef03-a198-ffb892324611%28Office.15%29.aspx) (CursorTypeEnum * _plCursorType_) **put_CursorType** (CursorTypeEnum _lCursorType_)
- [get_DataMember](https://msdn.microsoft.com/library/f89e1d42-7993-764b-4e8a-2f449903f792%28Office.15%29.aspx) (BSTR * _pbstrDataMember_) **put_DataMember** (BSTR _bstrDataMember_)
- [get_DataSource](https://msdn.microsoft.com/library/5c5d6c9b-b7d4-45a5-0f6a-a5580a74361e%28Office.15%29.aspx) (IUnknown ** _ppunkDataSource_) **putref_DataSource** (IUnknown * _punkDataSource_)
- [get_EditMode](https://msdn.microsoft.com/library/28ca8f14-abee-ad20-9c16-11bb36b487e4%28Office.15%29.aspx) (EditModeEnum * _pl_)
- [get_EOF](https://msdn.microsoft.com/library/f797e140-5572-1a4d-9afc-285f6a3868a8%28Office.15%29.aspx) (VARIANT_BOOL * _pb_)
- [get_Filter](https://msdn.microsoft.com/library/5abc528a-a6ee-34de-5d44-a3249194b0a0%28Office.15%29.aspx) (VARIANT * _Criteria_) **put_Filter** (VARIANT _Criteria_)
- [get_LockType](https://msdn.microsoft.com/library/1d2622dc-6cab-1b7f-98a8-97a41d5c047f%28Office.15%29.aspx) (LockTypeEnum * _plLockType_) **put_LockType** (LockTypeEnum _lLockType_)
- [get_MarshalOptions](https://msdn.microsoft.com/library/dc9c4e94-0725-210d-8251-079054541142%28Office.15%29.aspx) (MarshalOptionsEnum * _peMarshal_) **put_MarshalOptions** (MarshalOptionsEnum _eMarshal_)
- [get_MaxRecords](https://msdn.microsoft.com/library/424b2d41-073a-3fbe-30aa-99fac94f9a81%28Office.15%29.aspx) (long * _plMaxRecords_) **put_MaxRecords** (long _lMaxRecords_)
- [get_PageCount](https://msdn.microsoft.com/library/9cd8bf5c-b1e7-a453-4629-9cba7e408f53%28Office.15%29.aspx) (long * _pl_)
- [get_PageSize](https://msdn.microsoft.com/library/da56edd8-8947-aeff-2ef5-a8535c66575b%28Office.15%29.aspx) (long * _pl_) **put_PageSize** (long _PageSize_)
- [get_RecordCount](https://msdn.microsoft.com/library/e3072d10-5bf7-02a8-027e-a9d9a34e3f27%28Office.15%29.aspx) (long * _pl_)
- [get_Sort](https://msdn.microsoft.com/library/f2a39b7f-8b96-cd1a-8248-71f8b867454a%28Office.15%29.aspx) (BSTR * _Criteria_) **put_Sort** (BSTR _Criteria_)
- [get_Source](https://msdn.microsoft.com/library/523ea81e-d011-8d87-436e-084b6eba0908%28Office.15%29.aspx) (VARIANT * _pvSource_) **put_Source** (BSTR _bstrConn_) **putref_Source** (IDispatch * _pcmd_)
- [get_State](https://msdn.microsoft.com/library/ade0a50c-e2d8-23ac-4ea9-b012fedcd5db%28Office.15%29.aspx) (LONG * _plObjState_)
- [get_Status](https://msdn.microsoft.com/library/bf3ccb36-c985-5fae-4f76-c48a0e20e6f7%28Office.15%29.aspx) (long * _pl_)
- [get_StayInSync](https://msdn.microsoft.com/library/02c95c10-4032-14e1-e506-f334a8787142%28Office.15%29.aspx) (VARIANT_BOOL * _pbStayInSync_) **put_StayInSync** (VARIANT_BOOL _bStayInSync_)
- [get_Fields](https://msdn.microsoft.com/library/029aa738-8726-54a6-1813-b152813948bc%28Office.15%29.aspx) (ADOFields ** _ppvObject_)

## Events

- [EndOfRecordset](https://msdn.microsoft.com/library/8995b851-dff6-2525-1d62-a2cfb4f95393%28Office.15%29.aspx) (VARIANT_BOOL * _fMoreData,_ EventStatusEnum * _adStatus,_ _ADORecordset * _pRecordset_)
- [FetchComplete](https://msdn.microsoft.com/library/4863d5b5-7d77-bdef-c511-f85c9e6dec9d%28Office.15%29.aspx) (ADOError * _pError,_ EventStatusEnum * _adStatus,_ _ADORecordset * _pRecordset_)
- [FetchProgress](https://msdn.microsoft.com/library/09145d9a-ea5e-b41c-6c54-33ec83e642a9%28Office.15%29.aspx) (long  _Progress,_ long _MaxProgress,_ EventStatusEnum * _adStatus,_ _ADORecordset * _pRecordset_)
- [FieldChangeComplete](https://msdn.microsoft.com/library/bc4455a6-2925-33dc-d04f-8ea570e5e370%28Office.15%29.aspx) (LONG  _cFields,_ VARIANT _Fields,_ ADOError * _pError,_ EventStatusEnum * _adStatus,_ _ADORecordset * _pRecordset_)
- [MoveComplete](https://msdn.microsoft.com/library/fe7eb823-b388-6b3d-1ae9-056018032ef5%28Office.15%29.aspx) (EventReasonEnum  _adReason,_ ADOError * _pError,_ EventStatusEnum * _adStatus,_ _ADORecordset * _pRecordset_)
- [RecordChangeComplete](https://msdn.microsoft.com/library/b21229b2-74e6-0798-95bf-0252f041831c%28Office.15%29.aspx) (EventReasonEnum  _adReason,_ LONG _cRecords,_ ADOError * _pError,_ EventStatusEnum * _adStatus,_ _ADORecordset * _pRecordset_)
- [RecordsetChangeComplete](https://msdn.microsoft.com/library/2cec4cf9-a4e9-c386-5202-04e86f4cf8ad%28Office.15%29.aspx) (EventReasonEnum  _adReason,_ ADOError * _pError,_ EventStatusEnum * _adStatus,_ _ADORecordset * _pRecordset_)
- [WillChangeField](https://msdn.microsoft.com/library/bc4455a6-2925-33dc-d04f-8ea570e5e370%28Office.15%29.aspx) (LONG  _cFields,_ VARIANT _Fields,_ EventStatusEnum * _adStatus,_ _ADORecordset * _pRecordset_)
- [WillChangeRecord](https://msdn.microsoft.com/library/b21229b2-74e6-0798-95bf-0252f041831c%28Office.15%29.aspx) (EventReasonEnum  _adReason,_ LONG _cRecords,_ EventStatusEnum * _adStatus,_ _ADORecordset * _pRecordset_)
- [WillChangeRecordset](https://msdn.microsoft.com/library/2cec4cf9-a4e9-c386-5202-04e86f4cf8ad%28Office.15%29.aspx) (EventReasonEnum  _adReason,_ EventStatusEnum * _adStatus,_ _ADORecordset * _pRecordset_)
- [WillMove](https://msdn.microsoft.com/library/fe7eb823-b388-6b3d-1ae9-056018032ef5%28Office.15%29.aspx) (EventReasonEnum  _adReason,_ EventStatusEnum * _adStatus,_ _ADORecordset * _pRecordset_)

## See also

- [Access for developers forum](https://social.msdn.microsoft.com/Forums/office/home?forum=accessdev)
- [Access help on support.office.com](https://support.office.com/search/results?query=Access)
- [Access help on answers.microsoft.com](https://answers.microsoft.com/)
- [Access forums on UtterAccess](https://www.utteraccess.com/forum/index.php?act=idx)
- [Access developer and VBA programming help center (FMS)](https://www.fmsinc.com/MicrosoftAccess/developer/)
- [Access posts on StackOverflow](https://stackoverflow.com/questions/tagged/ms-access)

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]