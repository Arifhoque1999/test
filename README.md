# test
https://stackblitz.com/edit/stackblitz-starters-tcjrst?description=A%20create-react-app%20project%20based%20on%20react%20and%20react-dom&file=src%2FApp.js,src%2Findex.js&title=React%20Starter

# my side 
https://hilarious-tulumba-d4298a.netlify.app/Portfolio/home
https://codepen.io/jagadeshanh/pen/pNqLYX


<mat-toolbar>
  <div id="navbar">
    <div id="navbar-left">
      <mat-toolbar-row>
        <img
          id="web-logo"
          src="https://tse3.mm.bing.net/th?id=OIP.oFFZA5Wyj7uq_-m8Kt-C7wAAAA&pid=ImgDet&rs=1"
          alt="webLogo"
        />
        <button mat-icon-button (click)="sidenav.toggle()">
          <mat-icon>menu</mat-icon>
        </button>
      </mat-toolbar-row>
    </div>
    <div id="navbar-right">
      <app-navbar></app-navbar>
    </div>
  </div>
</mat-toolbar>

<mat-sidenav-container >
  <mat-sidenav #sidenav opened="true" mode="side" style="width: 200px">
    <mat-nav-list>
      <a mat-list-item class="custom-background1" outerLink="/sidebar"><span>Dashboard</span></a>
      <a mat-list-item class="custom-background" outerLink="/reports"><span>SAP Payment</span></a>
      <a mat-list-item class="custom-background" outerLink="/reports"><span>Reports</span></a>
      <a mat-list-item class="custom-background"><span>Help Line</span></a>
      <a mat-list-item class="custom-background"><span>SAP Payment</span></a>
      <a mat-list-item class="custom-background"><span>Reports</span></a>
      <a mat-list-item class="custom-background"><span>Help Line</span></a>
      <a mat-list-item class="custom-background"><span>Reports Setting</span></a>
      <a mat-list-item class="custom-background"><span>Ledger</span></a>
      <a mat-list-item class="custom-background"><span>Loans</span></a>
    </mat-nav-list>
  </mat-sidenav>

  <mat-sidenav-content>
    <div style="height: 89vh">
      <router-outlet></router-outlet>
      <app-dashboard></app-dashboard>
    </div>
  </mat-sidenav-content>
</mat-sidenav-container>


