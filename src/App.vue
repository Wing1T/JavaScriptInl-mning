<template>

  <div class="container-scroller">
    <div class="horizontal-menu">
      <Navbar />
    </div>

    <div class="container-fluid page-body-wrapper">
      <div class="main-panel">
        <div class="content-wrapper">
          <div class="row">
            <Welcomeback />
          </div>

          <div class="row">
            <div class="col-xl-6 grid-margin">
              <div class="row">

                <Users />
                <Projects />
              </div>

              <div class="row">
                <div class="col-md-12 stretch-card">
                  <div class="card">

                    <Downloads />

                  </div>
                </div>
              </div>
            </div>

            <div class="col-xl-6 grid-margin stretch-card">
              <div class="card">

                <TotalSaleChart/>

              </div>
            </div>
          </div>

          <div class="row">
            <div class="col-md-3 grid-margin stretch-card">

              <TotalSale/>

            </div>

            <div class="col-md-3 grid-margin stretch-card">

              <TotalPurchases />

            </div>

            <div class="col-md-3 grid-margin stretch-card">

              <TotalOrders />

            </div>

            <div class="col-md-3 grid-margin stretch-card">

              <TotalGrowth />

            </div>

          </div>

          <div class="row">
            <div class="col-xl-8 grid-margin stretch-card">

              <Tickets />

            </div>

            <div class="col-xl-4 grid-margin stretch-card">

              <Updates />

            </div>

          </div>

          <div class="row">
            <div class="col-xl-3 grid-margin stretch-card">

              <Distribution />

            </div>

            <div class="col-xl-9 grid-margin stretch-card">
              <div class="card">
                <div class="row">
                  <div class="col-md-7 col-lg-6 col-xl-7">

                    <SaleReport />

                  </div>

                  <div class="col-md-5 col-lg-6 col-xl-5">

                    <SalesReportOverview />

                  </div>
                </div>
              </div>

            </div>
          </div>

          <div class="row">
            <div class="col-md-12">

              <OpenInvoices />

            </div>
          </div>
        </div>

        <footer class="footer">

          <Footer />

        </footer>

      </div>
    </div>
  </div>
</template>

<script>
import Navbar from "./components/navbar/navbar";
import Welcomeback from "./components/navbar/welcomeback";
import Users from "./components/totals/users";
import Projects from "./components/totals/projects";
import Downloads from "./components/totals/downloads";
import TotalSaleChart from "./components/totals/totalSaleChart";
import TotalSale from "./components/totals/totalSales";
import TotalPurchases from "./components/totals/totalPurchases";
import TotalOrders from "./components/totals/totalOrders";
import TotalGrowth from "./components/totals/totalGrowth";
import Tickets from "./components/middleInfo/tickets";
import Updates from "./components/middleInfo/updates";
import Distribution from "./components/middleInfo/distribution";
import SaleReport from "./components/middleInfo/saleReport";
import SalesReportOverview from "./components/middleInfo/salesReportOverview";
import OpenInvoices from "./components/middleInfo/openInvoices";
import Footer from "./components/footer/footer"

export default {
  name: "app",
  components: {
    Navbar,
    Welcomeback,
    Users,
    Projects,
    Downloads,
    TotalSaleChart,
    TotalSale,
    TotalPurchases,
    TotalOrders,
    TotalGrowth,
    Tickets,
    Updates,
    Distribution,
    SaleReport,
    SalesReportOverview,
    OpenInvoices,
    Footer 
  }
};
</script>


