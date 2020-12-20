# DC Affordable Housing and Investment | DSPP Final Project

See the [project website](https://ncstabile17.github.io/dspp-final-project/) for the full analysis. 

Using a combination of data sources, I conduct an analysis of investment by the DC government in affordable housing and economic development. I use `ggplot` to visualize relationships between government investment and affordable housing production and conduct a geospatial analysis of affordable housing production since 2015. I then produce two machine learning models: one to predict DC government investment in a project and one to predict affordable housing units in a project. I test several model specifications using K-Nearest Neighbor and Random Forest algorithms. 

## Data 

For this analysis, I combine multiple sources produced by the DC government. The [DC FY19 Economic Development Return on Investment Data spreadsheet](https://dmped.dc.gov/sites/default/files/dc/sites/dmped/publication/attachments/Return%20on%20Investment%20Data_FY15-19_v3.xlsx) data set pulls together economic development investments from across a variety of agencies and programs in the DC government for FY15-19. The data set was created by the DC Deputy Mayor for Planning and Economic Development (DMPED) as required by the Economic Development Return on Investment Accountability Amendment Act of 2018. Fore more information see DMPED's [FY19 Economic Development Return on Investment Accountability Report](https://dmped.dc.gov/sites/default/files/dc/sites/dmped/publication/attachments/FY19%20ED%20Return%20on%20Investment%20Accountability%20Report.pdf).

The second source is a [database of affordable housing projects projects](https://octo.quickbase.com/db/bit4krbdh?a=q&qid=44) maintained by the DC Department of Housing and Community Development. These projects span a number of years, but most are after 2010. 

The final source is a data set of [affordable housing production and preservation projects](https://opendata.dc.gov/datasets/affordable-housing) that encompasses comprehensively covers affordable housing projects which started or completed since January of 2015. The data includes affordable housing projects (production and preservation, rental and for-sale) which were subsidized by DMPED, DHCD, DCHFA, or DCHA, and those which were produced as a result of Planned Unit Development (PUD) proffers or Inclusionary Zoning (IZ) requirements. This data was used only for mapping affordable housing projects.
