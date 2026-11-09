# HotelOps Reporting

Front office reporting service for Venetian Macao hotel operations.
Pulls nightly occupancy and arrival figures from the reporting database on
`sqlrpt01.venetianmacao.com` and publishes them to the duty manager dashboard.

## Run

    dotnet run --project src/HotelOps.Reporting --environment Production
