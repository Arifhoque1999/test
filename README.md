# test
https://stackblitz.com/edit/stackblitz-starters-tcjrst?description=A%20create-react-app%20project%20based%20on%20react%20and%20react-dom&file=src%2FApp.js,src%2Findex.js&title=React%20Starter

# my side 
https://hilarious-tulumba-d4298a.netlify.app/Portfolio/home
https://codepen.io/jagadeshanh/pen/pNqLYX

<p-sidebar [visible]="true" [position]="'left'" [style]="{'width': '200px'}">
  <div class="custom-background1" (click)="navigateTo('/sidebar')">Dashboard</div>
  <div class="custom-background" (click)="navigateTo('/reports')">SAP Payment</div>
  <div class="custom-background" (click)="navigateTo('/reports')">Reports</div>
  <div class="custom-background">Help Line</div>
  <div class="custom-background">SAP Payment</div>
  <div class="custom-background">Reports</div>
  <div class="custom-background">Help Line</div>
  <div class="custom-background">Reports Setting</div>
  <div class="custom-background">Ledger</div>
  <div class="custom-background">Loans</div>
</p-sidebar>

<div>
  <router-outlet></router-outlet>
  <app-dashboard></app-dashboard>
</div>

