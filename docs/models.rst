Models
======

A crosswalk between the tables published by California's Secretary of State
and the models in this Django application.

Common filings
--------------

+------------------------------+--------------------------+
| Source TSV                   | Django model             |
+==============================+==========================+
| FILER_FILINGS_CD             | FilerFilingsCd           |
+------------------------------+--------------------------+
| FILINGS_CD                   | FilingsCd                |
+------------------------------+--------------------------+
| SMRY_CD                      | SmryCd                   |
+------------------------------+--------------------------+
| CVR_E530_CD                  | CvrE530Cd                |
+------------------------------+--------------------------+
| TEXT_MEMO_CD                 | TextMemoCd               |
+------------------------------+--------------------------+


Campaign filings
----------------

+------------------------------+--------------------------+
| Source TSV                   | Django model             |
+==============================+==========================+
| CVR_SO_CD                    | CvrSoCd                  |
+------------------------------+--------------------------+
| CVR2_SO_CD                   | Cvr2SoCd                 |
+------------------------------+--------------------------+
| CVR_CAMPAIGN_DISCLOSURE_CD   | CvrCampaignDisclosureCd  |
+------------------------------+--------------------------+
| CVR2_CAMPAIGN_DICLOSURE_CD   | Cvr2CampaignDisclosureCd |
+------------------------------+--------------------------+
| CVR3_VERIFICATION_INFO_CD    | Cvr3VerificationInfoCd   |
+------------------------------+--------------------------+
| DEBT_CD                      | DebtCd                   |
+------------------------------+--------------------------+
| LOAN_CD                      | LoanCd                   |
+------------------------------+--------------------------+
| EXPN_CD                      | ExpnCd                   |
+------------------------------+--------------------------+
| F495P2_CD                    | F495P2Cd                 |
+------------------------------+--------------------------+
| CSV_F470                     | Appears deprecated       |
+------------------------------+--------------------------+
| RCPT_CD                      | RcptCd                   |
+------------------------------+--------------------------+
| S496_CD                      | S496Cd                   |
+------------------------------+--------------------------+
| S497_CD                      | S497Cd                   |
+------------------------------+--------------------------+
| S498_CD                      | S498Cd                   |
+------------------------------+--------------------------+
| F501_502_CD                  | F501502Cd                |
+------------------------------+--------------------------+
| SPLT_CD                      | SpltCd                   |
+------------------------------+--------------------------+

Lobbying filings
----------------

+------------------------------+--------------------------+
| Source TSV                   | Django model             |
+==============================+==========================+
| CVR_REGISTRATION_CD          | CvrRegistrationCd        |
+------------------------------+--------------------------+
| CVR2_REGISTRATION_CD         | Cvr2RegistrationCd       |
+------------------------------+--------------------------+
| CVR_LOBBY_DISCLOSURE_CD      | CvrLobbyDisclosureCd     |
+------------------------------+--------------------------+
| CVR2_LOBBY_DISCLOSURE_CD     | Cvr2LobbyDisclosureCd    |
+------------------------------+--------------------------+
| LOBBY_AMENDMENTS_CD          | LobbyAmendmentsCd        |
+------------------------------+--------------------------+
| F690P2_CD                    | F690P2Cd                 |
+------------------------------+--------------------------+
| LATT_CD                      | LattCd                   |
+------------------------------+--------------------------+
| LCCM_CD                      | LccmCd                   |
+------------------------------+--------------------------+
| LEMP_CD                      | LempCd                   |
+------------------------------+--------------------------+
| LEXP_CD                      | LexpCd                   |
+------------------------------+--------------------------+
| LOTH_CD                      | LothCd                   |
+------------------------------+--------------------------+
| LPAY_CD                      | LpayCd                   |
+------------------------------+--------------------------+

Other filings
-------------

+------------------------------+--------------------------+
| Source TSV                   | Django model             |
+==============================+==========================+
| ACRONYMS_CD                  | AcronymsCd               |
+------------------------------+--------------------------+
| ADDRESS_CD                   | AddressCd                |
+------------------------------+--------------------------+
| BALLOT_MEASURES_CD           | BallotMeasuresCd         |
+------------------------------+--------------------------+
| EFS_FILING_LOG_CD            | EfsFilingLogCd           |
+------------------------------+--------------------------+
| F690P2_CD                    | F690P2Cd                 |
+------------------------------+--------------------------+
| FILERNAME_CD                 | FilernameCd              |
+------------------------------+--------------------------+
| FILER_ACRONYMS_CD            | FilerAcronymsCd          |
+------------------------------+--------------------------+
| FILER_ADDRESS_CD             | FilerAddressCd           |
+------------------------------+--------------------------+
| FILER_ETHICS_CLASS_CD        | FilerEthicsClassCd       |
+------------------------------+--------------------------+
| FILERS_CD                    | FilersCd                 |
+------------------------------+--------------------------+
| FILER_INTERESTS_CD           | FilerInterestsCd         |
+------------------------------+--------------------------+
| FILER_LINKS_CD               | FilerLinksCd             |
+------------------------------+--------------------------+
| FILER_STATUS_TYPES_CD        | FilerStatusTypesCd       |
+------------------------------+--------------------------+
| FILER_TO_FILER_TYPE_CD       | FilerToFilerTypeCd       |
+------------------------------+--------------------------+
| FILER_TYPES_CD               | FilerTypesCd             |
+------------------------------+--------------------------+
| FILER_XREF_CD                | FilerXrefCd              |
+------------------------------+--------------------------+
| FILING_PERIOD_CD             | FilingPeriodCd           |
+------------------------------+--------------------------+
| GROUP_TYPES_CD               | GroupTypesCd             |
+------------------------------+--------------------------+
| HDR_CD                       | HdrCd                    |
+------------------------------+--------------------------+
| HEADER_CD                    | HeaderCd                 |
+------------------------------+--------------------------+
| IMAGE_LINKS_CD               | ImageLinksCd             |
+------------------------------+--------------------------+
| LEGISLATIVE_SESSIONS_CD      | LegislativeSessionsCd    |
+------------------------------+--------------------------+
| LOBBYING_CHG_LOG_CD          | LobbyingChgLogCd         |
+------------------------------+--------------------------+
| LOBBYIST_CONTRIBUTIONS1_CD   | LobbyistContributions1Cd |
+------------------------------+--------------------------+
| LOBBYIST_CONTRIBUTIONS2_CD   | LobbyistContributions2Cd |
+------------------------------+--------------------------+
| LOBBYIST_CONTRIBUTIONS3_CD   | LobbyistContributions3Cd |
+------------------------------+--------------------------+
| LOBBYIST_EMP_LOBBYIST1_CD    | LobbyistEmpLobbyist1Cd   |
+------------------------------+--------------------------+
| LOBBYIST_EMP_LOBBYIST2_CD    | LobbyistEmpLobbyist2Cd   |
+------------------------------+--------------------------+
| LOBBYIST_EMPLOYER1_CD        | LobbyistEmployer1Cd      |
+------------------------------+--------------------------+
| LOBBYIST_EMPLOYER2_CD        | LobbyistEmployer2Cd      |
+------------------------------+--------------------------+
| LOBBYIST_EMPLOYER3_CD        | LobbyistEmployer3Cd      |
+------------------------------+--------------------------+
| LOBBYIST_EMPLOYER_FIRMS1_CD  | LobbyistEmployerFirms1Cd |
+------------------------------+--------------------------+
| LOBBYIST_EMPLOYER_FIRMS2_CD  | LobbyistEmployerFirms2Cd |
+------------------------------+--------------------------+
| LOBBYIST_FIRM1_CD            | LobbyistFirm1Cd          |
+------------------------------+--------------------------+
| LOBBYIST_FIRM2_CD            | LobbyistFirm2Cd          |
+------------------------------+--------------------------+
| LOBBYIST_FIRM3_CD            | LobbyistFirm3Cd          |
+------------------------------+--------------------------+
| LOBBYIST_FIRM_EMPLOYER1_CD   | LobbyistFirmEmployer1Cd  |
+------------------------------+--------------------------+
| LOBBYIST_FIRM_EMPLOYER2_CD   | LobbyistFirmEmployer2Cd  |
+------------------------------+--------------------------+
| LOBBYIST_FIRM_LOBBYIST1_CD   | LobbyistFirmLobbyist1Cd  |
+------------------------------+--------------------------+
| LOBBYIST_FIRM_LOBBYIST2_CD   | LobbyistFirmLobbyist2Cd  |
+------------------------------+--------------------------+
| LOOKUP_CODES_CD              | LookupCode               |
+------------------------------+--------------------------+
| NAMES_CD                     | NamesCd                  |
+------------------------------+--------------------------+
| RECEIVED_FILINGS_CD          | ReceivedFilingsCd        |
+------------------------------+--------------------------+
| REPORTS_CD                   | ReportsCd                |
+------------------------------+--------------------------+
| S401_CD                      | S401Cd                   |
+------------------------------+--------------------------+


Empty files
-----------

+------------------------------+--------------------------+
| Source TSV                   | Django model             |
+==============================+==========================+
| FILER_TYPE_PERIODS_CD        |                          |
+------------------------------+--------------------------+
| LOBBYIST_EMPLOYER_HISTORY_CD |                          |
+------------------------------+--------------------------+
| LOBBYIST_FIRM_HISTORY_CD     |                          |
+------------------------------+--------------------------+
